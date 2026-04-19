# Testing the bash commands

bash date_test_bad will give this:

date_test_bad: rad 2: ${date +%Y-%m-%d}: felaktig substitution
date_test_bad: rad 3: oväntat filslut vid sökning efter matchande

## run the good command file
chmod+x date_good
bash date_good
