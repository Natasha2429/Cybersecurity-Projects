---> Description

This tool monitors changes in files by calculating and comparing SHA-256 hash values. It helps detect:

❌ Deleted files

⚠ Modified files

🔟 Newly added files

---> How to Run

Run the code in Jupyter Notebook or VS Code.

On first run, it creates a file (hashes.json) with SHA-256 hashes.

On second and subsequent runs, it compares hashes and alerts if any file is changed, removed, or added.

---> Inputs Required

Change the variable folder_to_monitor in the script:
folder_to_monitor = "test_files"
Replace test_files with the path of the folder you want to monitor.

