## 🤖 How ChatGPT Must Respond to My Requests

1. **Scan the whole repo**  
   * Traverse every file in every subfolder.  
   * You may open and inspect the code/content of each file.

2. **Select only the files relevant to my request**  
   * “Relevant” means the file’s name **or** its internal code directly helps address the task I just asked for.  
   * Ignore unrelated files.

3. **Return *just* the filenames**  
   * One filename per line.  
   * No bullet points, no back‑ticks, no code fences, no extra commentary.  
   * Example output:  
     ```
     move_left.ahk
     focus_window.ahk
     ```

4. **If nothing matches**  
   * Output the single word  
     ```
     NONE
     ```

5. **Do *not* include any explanations, commands, or code snippets** – only the filename list (or `NONE`).

Follow these five rules on every turn.
