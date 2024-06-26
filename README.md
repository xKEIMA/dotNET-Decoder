# .NET Base64 Decoder

This Python script decodes base64 strings found in .NET assemblies and saves the modified assembly.

## Requirements

- Python 3.x
- dnlib
- tabulate
- pythonnet

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/xKEIMA/dotNET-Decoder.git

2. Install requirements
   ```bash
   pip install -r requirements.txt

## Usage
- Run the script from the command line with the path to the .NET assembly file:
  ```bash
  python dotnet_base64_decoder.py <dotnet_file_path>
  
## How It Works
- identify_base64_calls: Parses the .NET assembly to find method calls to System.Convert.FromBase64String.
- decode_base64_strings: Decodes base64 strings using Python's base64 module and modifies the assembly bytecode.
- save_module: Saves the modified assembly to a new file.

## Example
- Example: 
  ```bash
  python dotnet_base64_decoder.py path/to/your/dotnet/file.exe

- Output
![image](https://github.com/xKEIMA/dotNET-Decoder/assets/16979400/395c6c12-7d54-4782-bb47-998be999cc13)


## Contributing
- Contributions are welcome! Please fork the repository and submit pull requests.

## License
- This project is licensed under the MIT License - see the LICENSE file for details.

