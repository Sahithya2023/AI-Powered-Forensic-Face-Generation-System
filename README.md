# AI-Powered Forensic Face Generation System (Prototype)

## Project Overview
This project is an AI-powered forensic face generation system that creates realistic suspect faces from witness descriptions using diffusion-based generative models.

The system converts facial attributes such as age, gender, eyes, nose, hair, and skin tone into structured prompts and generates multiple suspect face variations.

## Problem Statement
Traditional forensic sketch creation depends heavily on manual artists and witness memory, making the process slow, subjective, and inconsistent.

## Solution
Developed an intelligent face reconstruction system that:

- Captures witness-described facial features step-by-step
- Applies confidence-based weighting for uncertain attributes
- Generates realistic suspect faces using Stable Diffusion
- Produces multiple candidate face variations
- Supports iterative refinement while preserving identity

## Features
- Guided witness input interface
- Confidence-based facial feature weighting
- Realistic AI face generation
- Multiple suspect face variations
- Identity-preserving image refinement
- Interactive Streamlit UI
- CPU-compatible prototype workflow

## Tech Stack
- Python
- PyTorch
- Streamlit
- Stable Diffusion
- Diffusers
- PIL / Image Processing

## Model Pipeline
- Attribute Input Collection
- Prompt Engineering
- Confidence Weight Mapping
- Diffusion-Based Image Generation
- Face Variation Sampling
- Image Refinement

## Business / Real-World Applications
- Police suspect reconstruction
- Missing person simulation
- Criminal investigation support
- Witness-assisted face generation
- Digital forensics research

## Future Improvements
- Faster CPU inference
- South Asian facial realism enhancement
- Web deployment
- Real-time witness editing tools
- Fine-tuned custom diffusion model

## Run

```bash
streamlit run forensic_face_app_v2.py
