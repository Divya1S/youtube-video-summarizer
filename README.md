# YouTube Video Summarizer
A Python tool that generates concise summaries of YouTube videos by extracting transcripts and leveraging AI-powered summarization models. Perfect for quickly understanding video content without watching the entire video.

## Features
- Extracts transcripts from YouTube videos using `youtube-transcript-api`.
- Summarizes transcripts into a concise format using Hugging Face's BART model.
- Optimized for handling long transcripts by chunking text and summarizing in parts.
- Supports GPU acceleration for faster processing (if available).
