# scripting-utils

General-purpose Bash and Python scripts for file management, data processing, and automation.

---

## file_management/

| Script | Language | Description |
|--------|----------|-------------|
| [backup_folder](file_management/backup_folder/) | Bash | Create timestamped backups of any folder |
| [collect_file_extensions](file_management/collect_file_extensions/) | Bash | List all unique file extensions in a directory tree |
| [find_large_files](file_management/find_large_files/) | Bash | Find files above a size threshold, sorted by size |
| [rename_spaces_to_underscores](file_management/rename_spaces_to_underscores/) | Bash | Rename files and folders by replacing spaces with underscores |
| [run_command_in_subfolder](file_management/run_command_in_subfolder/) | Bash | Run any shell command inside every subfolder of a directory |
| [change_any_line](file_management/change_any_line/) | Bash | Replace any line across many files (exact, contains, or regex mode; dry-run support) |

## data_processing/

| Script | Language | Description |
|--------|----------|-------------|
| [arbitrary_line_removal](data_processing/arbitrary_line_removal/) | Python | Remove specific lines from text files by line number or pattern |
| [clean_numpy_trajectories](data_processing/clean_numpy_trajectories/) | Python | Slice and clean `.npy` trajectory arrays |
| [line_pattern_extractor](data_processing/line_pattern_extractor/) | Python | Extract lines matching a keyword pattern and export to Excel |
| [transcript_cleaning](data_processing/transcript_cleaning/) | Python | Clean and normalize raw transcript text files |
| [structured_record_extractor](data_processing/structured_record_extractor/) | Python | Extract fields from structured text files into CSV using user-defined regex patterns |

## automation/

| Script | Language | Description |
|--------|----------|-------------|
| [batch_folder_runner](automation/batch_folder_runner/) | Python | Run any shell command across a batch of folders |
| [open_images](automation/open_images/) | Bash | Open all images in a folder with the system viewer |
| [open_iteratively](automation/open_iteratively/) | Bash | Interactively step through simulation folders and open matching files one by one |

## docs/

| Script | Language | Description |
|--------|----------|-------------|
| [adding_blank_page](docs/adding_blank_page/) | Python | Insert blank pages into a PDF at specified positions |

---

## Requirements

```bash
pip install -r requirements.txt
```

The Bash scripts have no Python dependencies.
