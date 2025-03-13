# genimi
A package to access Google Gemini API in Emacs. Fetch from the Google Gemini API on emacs.

# Installation

1. Download repository in local machine.
2. In the config file of emacs type:
   ```
   (add-to-list 'load-path "<path_to_directory_which_contains_genimi.el>")
	   (require 'genimi)
   ```
3. Set Gemini API key using
   ```
   (customize-save-variable 'GeminiKey "<GEMINI_API_KEY>")
   ```
4. You are done.

# Usage

Genimi can be invoked using `C-c g` keys. It selects the text from the current line and sends as prompt to the Gemini server and prints the response in the next line of same buffer.


![demo](demo/genimi2.gif "Demo")
