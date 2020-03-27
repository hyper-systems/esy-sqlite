

$(TARGET_DIR)/test.exe: test.c
	gcc $^ -o $@ -lsqlite3 \
		`pkg-config --cflags sqlite3` \
		`pkg-config --libs sqlite3`


.PHONY: test
test: $(TARGET_DIR)/test.exe
	$(TARGET_DIR)/test.exe

