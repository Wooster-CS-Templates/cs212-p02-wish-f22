wish:
	gcc wish.c -Wall -Werror -o wish

test:
	./test-wish.sh

gh-test: clean wish test

clean:
	rm -f wish
	rm -rf tests-out