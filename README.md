# test_file_type

The `test_file_type` script is a versatile and multilingual utility designed to analyze and report detailed information about a given file. This tool can identify various file types, including directories, symbolic links, pipes, character/block devices, sockets, and regular files. It also provides specific details for images, audio, video, PDFs, and compressed files. Additionally, this script is part of the [shell_utils](https://github.com/felipefacundes/shell_utils) framework, one of the most comprehensive collections of scripts and utilities for user facilitation.

## Features

- **Multilingual Support**: Messages are provided in English, Portuguese, French, and German based on system language.
- **Detailed File Analysis**:
  - Identifies file types such as directories, symbolic links, and pipes.
  - Extracts metadata for media files (images, audio, video).
  - Counts pages for PDF documents.
  - Calculates uncompressed sizes for compressed files.
- **Integration**: Functions seamlessly within the `shell_utils` framework, enhancing user productivity.

## Installation

Clone the repository to get started:

```bash
git clone https://github.com/felipefacundes/test_file_type
```

Navigate to the `test_file_type` script location:

```bash
cd test_file_type
```

## Usage

Run the script by passing a file path as an argument:

```bash
./test_file_type <file_path>
```

### Example

```bash
./test_file_type example.pdf
```

## Requirements

Some advanced features may require the following tools to be installed:

- `file`
- `identify` (ImageMagick)
- `ffprobe` (FFmpeg)
- `mediainfo`
- `pdfinfo`

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests. For issues or suggestions, please use the GitHub issue tracker.

---

Explore more scripts and utilities in the [shell_utils](https://github.com/felipefacundes/shell_utils) framework.

## License

This script is licensed under the GPLv3. See the LICENSE file in the [shell_utils repository](https://github.com/felipefacundes/shell_utils) for details.

## Credits

Developed by Felipe Facundes as part of the shell_utils framework.

