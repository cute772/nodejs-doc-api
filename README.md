# nodejs-doc-api
+ node doc api for me
+ https://nodejs.org/ko/docs/

## File System

### fs.open(file, flags[, mode], callback)

### fs.read(fd, buffer, offset, length, position, callback)
+ fd : 파일디스크립터
+ Read data from the file specified by fd.
+ buffer : 읽은 내용을 담을 버퍼( let buf = Buffer.alloc(10) )
+ buffer is the buffer that the data will be written to.
+ offset : 버퍼 오프셋(덮어쓸 버퍼 시작 위치)
+ offset is the offset in the buffer to start writing at.
+ length : 읽을 사이즈
+ length is an integer specifying the number of bytes to read.
+ position : 어디서부터 읽을지 정하는 포지션(위치값) 4로 지정할 경우 4byte 부터 읽는다(0부터 시작함.. 주의)
+ position is an argument specifying where to begin reading from in the file. If position is null, data will be read from the current file + position, and the file position will be updated. If position is an integer, the file position will remain unchanged.

### fs.close(fd, callback)

### fs.stats(fd, callback)


