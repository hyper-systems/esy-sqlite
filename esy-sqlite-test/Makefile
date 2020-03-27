

_build/test.exe: test.c
	gcc $^ -o $@ -lsqlite3 \
		`pkg-config --cflags sqlite3` \
		`pkg-config --libs sqlite3`


.PHONY: test
test: _build/test.exe
	_build/test.exe

