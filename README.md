These are datasets from various sources curated by us using our AI and infrastructure.

-"text_input.jsonl" files are the complete corpus of text.
  The text was chunked to blocks within a 512 token limit.

-"qa_input.jsonl" is a tripplicate input/response set. 
  Each chunk from the text_input.jsonl was given to the AI.
  The AI was instructed to generate a question, a statement and a lie based on the chunk's contents.
  The AI was then instructed to respond to the inputs using only the contents of the chunk as its source of truth.

  
