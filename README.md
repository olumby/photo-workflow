# Photo Workflow

### Aim

The aim of this project is to wrap exiftool and any other tools needed, receive a directory of scanned photos, loop through them and apply titles, metadata, etc based on user input.

My CanoScan LiDE 400 scans photos well, even splits single scans into multiple photos, but it can't solve the organisation problem. The result should be well named photos with metadata like Location, Camera, Date, etc ready to be imported into Apple Photos. By request, there should also be an option to burn on captions.

Workflow:

- Scan photos from album
- Run script to apply generic metadata, naming scheme, etc
- Add specific captions to specific photos (burn in/metadata)
