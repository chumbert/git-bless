# Blessing-Based Development (BBD)

Tired of writing hundreds of tests to reach your coverage threshold and still experience bugs in production ?

Tired of long manual testing sessions that leave you more worried than before ?

Tired of complex quality processes that produces documents instead of reliability ?

**Then blessing-based developement (BBD) is for you.**

BBD tackles the issue at the root and replaces all these pains with strong, battle-tested, blessings of the code before it is committed and shipped into your environments.
BBD doesn't leave you with endless test maintenance tasks and shortens the quality process to the extreme without conceding an ounce of rationality for your software's robustness*.

<sup>*While we're confident in the quality of our blessings, it is recommended to run your code on blessed hardware (coming soon in our cloud services).</sup>

# Testimonials

"Embracing a blessing-based approach for our software deployments has brought a divine touch to our coding endeavors. Witnessing the seamless integration of our blessed code has been nothing short of a miracle. We are grateful for the guidance and spiritual harmony that accompanied this sacred process."  
*Matthew Thompson Co-founder of SeraphicSystems*


"Choosing to infuse our software deployments with the power of blessings has been a spiritual journey for our development team. The divine grace that envelops our code brings not only functionality but a sense of purpose. Our projects now carry the mark of a higher calling, and we couldn't be more blessed by the results."  
*Sarah Davis, CBO at BlessedByte Technologies*

# Coming soon

Here's a sneak peek of the git-bless roadmap:

* Embedded proof-of-blessing in commits,
* Branches and tags blessing,
* Bless your artifacts right in time by using our GitHub action for your packaging and deployment.
* Blessings for culture not founded on christianity (contributions welcome).

# Instructions

Clone this repository, mark `git-bless` as executable and add the directory to your path.

```shell
git clone git@github.com:chumbert/git-bless.git
chmod +x git-bless/git-bless
```

If you're using zsh:
```shell
echo "export PATH=\$PATH:$(pwd)/git-bless"  >> ~/.zshrc
source ~/.zshrc
```

Voila ! You can now stage your changes and bless them before committing by using:
```bash
git bless
```

Example run:
```
❯ git bless
✝ Blessing        3 changed files.
✝ Estimated number of blessings required: 1.58496250072115618146.
✝ Blessing 2 times to be safe.
✝ Blessing:
	complex_script_for_production.sh
	harmless_database_migration.sql
	unreadable_configuration_file.yaml

✝✝✝ Sanctus Spiritus, veni in auxilium nostrum. Emitte caelitus lucis tuae radium. Amen. ✝✝✝

✝✝✝ Sub umbra alarum tuorum, Domine, protege nos. Amen. ✝✝✝

✝✝✝ In nomine Patris, et Filii, et Spiritus Sancti, sub divinae tutelae potentia te ponimus. Custos angelorum te defendat et custodiat, teque ab omni malo tueatur. Amen. ✝✝✝

✝ Done blessing:
	✝ complex_script_for_production.sh
	✝ harmless_database_migration.sql
	✝ unreadable_configuration_file.yaml
✝ You can now safely commit these files.
```
