So install lolcommits and the dependency of Ruby via rvm.

1. lolcommits --enable --delay=5 --animate=4 --fork
2. vi ~/path/to/proj/.git/hooks/post-commit
3. add LOLCOMMITS_DIR=~/path/to/proj/.lolcommits lolcommits --enable --delay-5 --animate-4 --fork
