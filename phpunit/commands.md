PHPUnit Commands
================

Run each test individually

    find ./ -name \*.php -exec echo {} \; -exec ../bin/phpunit --colors --process-isolation {} \;

Run strace on frozen tests

    strace -ff -s 1000 command 2>&1 | grep -v gettimeofday
