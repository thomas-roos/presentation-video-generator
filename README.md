# Presentation Video Generator

AI-powered tool that creates professional presentation videos using Amazon Q for content research, AWS Polly for narration, and FFmpeg for video assembly.

## Usage

```bash
./quick-presentation "Your Topic" [slides] [voice]
```

## Examples

```bash
./quick-presentation "CMake Policies" 3 Amy
./quick-presentation "Docker" 2
./quick-presentation "Kubernetes" 4 Matthew
```

## Requirements

- Amazon Q CLI (`q`)
- AWS CLI with Polly access
- ImageMagick (`convert`)
- FFmpeg

## License

GPLv3
