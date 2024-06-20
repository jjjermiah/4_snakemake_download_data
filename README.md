# This example uses conda environments within rules 

```json
{
  "conda_env_file_path": "pipeline_env.yaml",
  "config_file_path": "config/config.yaml",
  "git_url": "https://github.com/jjjermiah/4_snakemake_download_data.git",
  "output_files": [
    "results/output.txt"
  ],
  "pipeline_name": "4_snakemake_download_data",
  "snakefile_path": "workflow/Snakefile"
}
```