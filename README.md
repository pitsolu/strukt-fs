Strukt Fs
=========

Basic filesystem functionality. 

## Usage

```php
Strukt\Fs::isFile(file) //File Exists
Strukt\Fs::isPath(path) //Path Esists
Strukt\Fs::cat(file) //Dump File Contents
Strukt\Fs::touch(file) //Create File
Strukt\Fs::touchWrite(file, contents) //Create Write To File
Strukt\Fs::rename(from, to) //Rename File
Strukt\Fs::overwrite(file, contents) //Overwrite File Contents
Strukt\Fs::appendWrite(file, contents) //Append Contents To File
Strukt\Fs::rm(file) //Delete File
Strukt\Fs::rmdir(dir) //Recursively Delete
Strukt\Fs::mkdir(dir) //Recursively Create
Strukt\Fs::isWritable(file) //Check If File Is Writeable
Strukt\Fs::isReadable(file) //Check If File is Readable
Strukt\Fs::copyRecur(source,destination) //Copy recursively
Strukt\Fs::cpr(source,destination) //Alias for copyRecur
```