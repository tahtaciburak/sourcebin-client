# SourceBin Client
A python script that submit pastes into sourcebin easily.

## Installation Steps
1. Download the python script
2. Set your interpreter's location on top of file.
3. Move script into /usr/bin 

## Usage

```bash
cat /path/to/file.txt | sourcebin
cat /my/secret/file.txt | sourcebin --secret <password>
cat /my/file.txt | sourcebin --expiration <year|month|day|hour|minute>
```
