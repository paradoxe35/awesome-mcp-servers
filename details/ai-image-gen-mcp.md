# Ai Image Gen Mcp

An open-source MCP (Model Context Protocol) server for generating images from text prompts using Replicate's black-forest-labs/flux-schnell model. Designed for extensibility and full protocol compliance, it can be used with any MCP client.

**Source:** [github.com/mikeyny/ai-image-gen-mcp](https://github.com/mikeyny/ai-image-gen-mcp)

## Features
- Generate images from text prompts via Replicate's model
- Configurable image parameters:
  - Resolution (megapixels: "1", "2", "4")
  - Aspect ratio ("1:1", "4:3", "16:9")
  - Output format ("webp", "png", "jpeg")
  - Compression quality (1-100)
  - Number of outputs (1-4)
  - Number of inference steps (4-20)
  - Fast generation mode option (go_fast)
  - Specify output directory and filename
- Full compliance with MCP protocol
- Error handling and validation (validation errors, API errors, server errors, unknown errors)
- Save generated images to a chosen directory
- Designed to work with Cursor's MCP feature, but compatible with any MCP client
- TypeScript implementation

## API Parameters
| Parameter            | Type    | Required | Default  | Description                                          |
|---------------------|---------|----------|----------|------------------------------------------------------|
| prompt              | string  | Yes      | -        | Text prompt for image generation                     |
| output_dir          | string  | Yes      | -        | Directory to save generated images                   |
| go_fast             | boolean | No       | false    | Enable faster generation mode                        |
| megapixels          | string  | No       | "1"      | Resolution quality                                   |
| num_outputs         | number  | No       | 1        | Number of images to generate (1-4)                   |
| aspect_ratio        | string  | No       | "1:1"    | Aspect ratio                                         |
| output_format       | string  | No       | "webp"   | Image format                                         |
| output_quality      | number  | No       | 80       | Compression quality (1-100)                          |
| num_inference_steps | number  | No       | 4        | Number of denoising steps (4-20)                     |

## Error Handling
- Validation errors (invalid parameters)
- API errors (Replicate API issues)
- Server errors (filesystem, permissions)
- Unknown errors (unexpected issues)
- Each error includes:
  - Error code
  - Human-readable message
  - Detailed error information

## Prerequisites
- Node.js 16+
- Replicate API token
- TypeScript SDK for MCP

## License
ISC

## Pricing
- No pricing information provided; this is an open-source project.

## Tags
`mcp` `image-generation` `generative-ai` `open-source` `replicate`