# Setting up a langchain environment using Anaconda prompt. 
### creates a new environment called langchain_env
```
conda create --name langchain_env python=3.12.7
```
### lists all your environments
```
conda env list //lists your
```
### activates your langchain_env
```
conda activate langchain_env
```
### check the python version you're running. 
```
python -V
```
### install python-dotenv, ipykernel, jupyterlab, notebook
```
pip install openai python-dotenv ipykernel jupyterlab notebook
```
- openai => allows us to make calls to openai's api. 
- python-dotenv => allows us to set openai's api key as an env-variable.
```
python -m ipykernel install --user --name langchain_env
```
## To Delete your Conda Env(Kernel) 
### 1. Deactivate the environment. 
```
conda deactivate
```
### 2. remove the conda env. 
```
conda remove --name langchain_env --all
```

## important concepts to understand. 
The ** .ipynb_checkpoints **  folder is automatically created by Jupyter Notebook (and JupyterLab) to store backup versions of notebooks that you're working on. It is a hidden folder, meaning it starts with a dot (.), and you generally don’t need to interact with it directly.

Purpose of ** .ipynb_checkpoints: **
Automatic Backups: Jupyter creates checkpoints (backup copies) of the notebooks as you work on them. This is helpful in case the system crashes or you accidentally delete something important. It allows you to restore previous versions of your notebook.
Checkpoint Files: These backup files are stored in the .ipynb_checkpoints folder. You won’t see them in your regular notebook interface, but they exist as versions of your notebook saved at certain points during your work.

## As you know I am a huge fan of Keyboard shortcuts. 😉😉 Here are a few to boost your efficiency using JupyterNotebook. 😏
### Command Mode Shortcuts (press Esc to enter command mode)
	1. A: Insert a new cell above the current cell. </br>
	2. B: Insert a new cell below the current cell.</br>
	3. M: Change the current cell to Markdown.</br>
	4. Y: Change the current cell to Code.</br>
	5. D, D: Delete the current cell (press D twice).</br>
	6. Z: Undo the deletion of a cell.</br>
	7. C: Copy the current cell.</br>
	8. X: Cut the current cell.</br>
	9. V: Paste the copied/cut cell below the current one.</br>
	10. Shift + V: Paste the copied/cut cell above the current one.</br>
	11. Shift + Up/Down: Extend the selection of cells.</br>
	12. Ctrl + S: Save the notebook.</br>
	13. Shift + Enter: Run the current cell and move to the next one.</br>
	14. Ctrl + Enter: Run the current cell and stay on it.</br>
	15. Alt + Enter: Run the current cell and insert a new one below.</br>
	16. Shift + Space: Scroll up.</br>
	17. Space: Scroll down.</br>
	18. H: Show all keyboard shortcuts.</br>
	19. Arrow Up (Move to the cell above): K (in Command Mode)
        20. Arrow Down (Move to the cell below): J (in Command Mode)
 
### Edit Mode Shortcuts (press Enter to enter edit mode)
	1. Ctrl + A: Select all content in the cell.</br>
	2. Ctrl + C: Copy the selected content.</br>
	3. Ctrl + X: Cut the selected content.</br>
	4. Ctrl + V: Paste the content.</br>
	5. Ctrl + Z: Undo the last change.</br>
	6. Ctrl + Shift + Z: Redo the last undone change.</br>
	7. Ctrl + Shift + -: Split the cell at the cursor position.</br>
	8. Tab: Autocomplete or indent (depending on context).</br>
	9. Shift + Tab: Show tooltip/help (useful for functions or methods).</br>
 	10. Shift: Show suggestion of other similar functions with the same stem
### Command Mode:</br>
	• Command mode is the state in which you can interact with and manage cells at a higher level.</br>
	• In command mode, the focus is on the cells themselves (like moving cells up or down, deleting, running, etc.), and the cell border will be blue.</br>
	• You cannot edit the content of the cells directly in command mode, but you can perform actions like:</br>
		○ Inserting new cells (A for above, B for below).</br>
		○ Deleting cells (D, D to delete a cell).</br>
		○ Changing the cell type (code or markdown) (M for Markdown, Y for code).</br>
		○ Running cells (Shift + Enter to run and move to the next cell).</br>
To enter command mode, you press Esc when you are in the notebook. The cell border will turn blue, indicating that you are in command mode.</br>
### Edit Mode:</br>
	• Edit mode is the state where you can edit the content of the cells (like writing or modifying code in a code cell or writing text in a markdown cell).</br>
	• In edit mode, the cell border will be green, and the cursor will be inside the cell, so you can type directly into it.</br>
To enter edit mode, you press Enter while selecting a cell. Once you're done editing, you can press Esc to go back to command mode.</br>
**Summary:** </br>
	• Command mode: You manage cells as a whole (blue border, press Esc to enter).</br>
	• Edit mode: You edit the content of a cell (green border, press Enter to enter).</br>
The difference is important because many keyboard shortcuts depend on whether you're in command or edit mode. For example, Shift + Enter runs the cell when you're in command mode, but when you're in edit mode, it will just move the cursor down in the cell.</br>

### To Enter Edit Mode:</br>
	• Simply press Enter when you are in command mode. This will place the cursor inside the selected cell, allowing you to edit the content.</br>
### To Enter Command Mode:</br>
	• Press Esc when you are in edit mode. This will exit edit mode and return you to command mode, where you can manage cells but not directly edit their content.</br>

