# gt-itemsdat-json
Python 3.11 tool to convert/parse Growtopia's items.dat file into a JSON format.

## Usage
Ensure you have Python 3.11 installed. To run the script, use the following command:

```bash
py itemsdat-json <path to items.dat>
``` 

### Saving Output to a File
If you want to save the output to a file instead of printing it to the console, you can redirect the output using shell redirection like this:

```bash
py itemsdat-json <path to items.dat> > output.json
```
This will save the output to `output.json` instead of printing it to the console.

### Troubleshooting
If you encounter any issues, the parser may be outdated. In that case, consider editing the template.py file to accommodate any changes. Additionally, you can use the itemsdat-info script to understand what changes the new version introduces:
```bash
py itemsdat-info <path to items.dat>
``` 

## Docs
For detailed information about the properties of `items.dat`, please refer to the following resource by @H-pun. Contributions to this documentation are much appreciated:

- [Items.dat Documentation](https://github.com/H-pun/growtopia-api/blob/master/docs/itemsdat.md)

## Credits and References
- GrowDocs by [@iProgramMC](https://github.com/iProgramMC/GrowDocs) (forked from [@GrowtopiaNoobs](https://github.com/GrowtopiaNoobs/GrowDocs))
- Updated docs by [@H-pun](https://github.com/H-pun/growtopia-api/tree/master/docs)