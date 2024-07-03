# Hyperledger Labs

Hyperledger Labs provides a space (i.e., GitHub repos) where work can
easily be started without the creation of a project. Please refer to
the [Hyperledger Labs wiki page](https://wiki.hyperledger.org/display/labs)
for additional information.

## Process to propose a new lab

1. Fork the [hyperledger-labs.github.io](https://github.com/hyperledger-labs/hyperledger-labs.github.io) repository.

2. Fill out the [Proposal Template](https://github.com/hyperledger-labs/hyperledger-labs.github.io/blob/master/proposal-template.md)
and save it into the `labs` subdirectory under the name of your lab,
such as `labs/mynewlab.md`. It is expected that your lab repository will have
the same name so keep that in mind.

3. In the Proposal Template, there is an entry for sponsor(s). Although not required, proposers are encouraged to seek a sponsor who can help them create ties with the rest of the Hyperledger community and ensure that the proposal is cogent and novel (in conception, proposed execution, or interested community).<br/><br/>
To find sponsors:
   1. use your connections to existing projects and ask maintainers,
   2. find working groups or projects with affinities to the proposed lab and pitch the project (good to have the template already filled out) in associated channels and/or mailing lists. The WG chairs emails, the maintainers contacts etc can be found on the wiki or github. Make personal appeals if you can. Every repository contains a MAINTAINERS file that lists the current maintainers with their contact information and you can reach them all by posting to the [Maintainers list](https://lists.hyperledger.org/g/maintainers).

4. Commit your changes with proper sign-off. This means that your commit
log message must contain a line that looks like the following one,
with your actual name and email address:

        Signed-off-by: John Doe <john.doe@example.com>

   Adding the `-s` flag to your `git commit` command will add that line
automatically. You can also add it manually as part of your commit
log message or add it afterwards with `git commit --amend -s`.

5. Submit a Pull Request.

The labs stewards will then review your proposal. Like sponsors, stewards do not have a responsibility beyond this; ongoing work like contributing code or reviews is not tied to their role as stewards. In reviewing the proposal, the stewards make sure that the proposal is cogent and novel (in conception, proposed execution, or interested community). 

**IMPORTANT:** It is up to the proposer to ensure that any comments or requested changes by the lab stewards are addressed. Failure to do so may delay the approval of your proposal.

## Bringing in an existing repository

By default the Lab stewards will create a new repository for you to
start from but if you have an existing github repo you would like to
bring to your proposed lab you have the option to request for that
repo to be reused instead. This is however only possible if every
commit in your existing repo is signed-off so there is no
[DCO](https://developercertificate.org/) related issues. If that is
not the case, you have two options:

1. bring your code by squashing all of your commits into a single first commit made against your new lab repo with your sign-off.

2. amend the commit history to include DCO sign-off for each of the commits. The Hyperledger Indy community has [documented steps to fix DCO on previous commits](https://github.com/hyperledger/indy-sdk/blob/main/docs/contributors/signing-commits.md#how-to-sign-previous-commits). Also, the [Fix DCO Guide from src-d](https://github.com/src-d/guide/blob/master/developer-community/fix-DCO.md) contains some different steps you can take.

**IMPORTANT:** Regardless of which option you use, please be sure that the past committers to your project agree to the [DCO](https://developercertificate.org/).

## Archiving

Stewards are responsible for curating the set of labs, archiving (see below) those that become dormant or unresponsive for an extended period (3+ months), or are explicitly deemed by the committers to be deprecated/obsoleted.

Deprecated, obsoleted, or dormant labs (as defined above) [will be marked as "archived" in GitHub](https://github.com/hyperledger-archives/iroha-scala/blob/ec206117d2bea6bdb73d14c35bc46092f82ebb3f/.github/settings.yaml#L8); that signifies that the lab is no longer maintained. Archived labs are read-only, and they can be moved back out of the [archives](https://github.com/hyperledger-labs/hyperledger-labs.github.io/tree/main/labs/archived), if there is interest in reviving them.

## License requirement

All Hyperledger software must be made available under an [Apache 2.0
license](LICENSE).
This applies to Labs. Please, make sure to license all incoming code
and new code accordingly, and ensure that all commits are made with
proper sign-off so that no [DCO](https://developercertificate.org/)
related issue is introduced.

## Code of Conduct

All Hyperledger community members must adhere to the
[Code of Conduct](https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct).
