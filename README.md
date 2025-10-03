# aws-polly-health-audio
A demo project using AWS Polly to convert health messages into audio, with a simple front-end for playback.


## The Problem
In many rural areas of Nigeria, public health information is mostly shared in written form (posters, flyers, text-heavy materials).  
However, **many people cannot read fluently** or may not engage with these materials.  
This creates a gap in awareness and access to essential health knowledge.  

## Solution
This project is a demo that uses Amazon Polly to convert selected health messages into audio (MP3) format. The audio files are then hosted on a simple webpage where users can play,download and listen easily.
This can serve as a **demo booth** for how technology can make health education more accessible.

## Tech Stack
- **Frontend:** HTML, CSS  
- **Cloud Service:** AWS Polly (Text-to-Speech)  
- **Storage/Hosting:** AWS S3 or local server   

## Future Improvement
- Build an **IVR** (using AWS Connect) so people can call a number to listen.
