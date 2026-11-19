# File Naming Conventions

A consistent naming convention makes files easier to identify, sort,
search and manage.

## General rules

When creating file names:

1.  **Be descriptive:** Use meaningful names that explain the content of
    the file.
2.  **Be consistent:** Apply the same naming structure throughout the
    project.
3.  **Use dates:** When relevant, use the ISO 8601 format: `YYYYMMDD`.
4.  **Avoid spaces:** Use underscores (`_`) or hyphens (`-`) as
    separators.
5.  **Use lowercase:** This helps avoid compatibility problems between
    operating systems.
6.  **Avoid special characters:** Do not use characters such as
    `/ \\ : * ? " < > |`.
7.  **Keep names reasonably short:** Include essential information
    without making file names unnecessarily long.
8.  **Use leading zeros:** For numbered files, use `001`, `002`, `003`
    instead of `1`, `2`, `3`.
9.  **Avoid personal or sensitive information:** Never include personal
    data in file or folder names.
10. **Avoid ambiguous terms:** Do not use names such as `final`,
    `final_new`, `final_revised` or `latest`.

## Suggested naming structure

A useful general format is:

`data_project-name-type-of-document_version.extension`
`2026-10-26_bacterialX_consent-form-approved_v01.docx`

or 

`project_sample_analysis_reference_date_version.extension`
`bacterialX_sample001_variantcalling_refNC_014246_20261117_v001.vcf.gz`
where
----------------------------------------------------------------------------------------
Field        Value             Description
----------------------------------------------------------------------------------------
project      bacterialX        Project name or acronym
sample       sample001         Unique sample identifier
analysis     variantcalling    Type of analysis performed
reference    refNC_014246      Reference genome identifier
date         20261117          Date associated with file generation (YYYYMMDD)
version      v001              File or result version
extension    .vcf.gz           File format: Variant Call Format compressed with gzip
----------------------------------------------------------------------------------------

Other examples:

``` text
microbiome_sample001_metagenomics_20261110_raw.fastq.gz
microbiome_sample001_metagenomics_20261112_cleaned.fastq.gz
microbiome_sample001_taxonomic_profile_20261115_v001.tsv
microbiome_differential_analysis_20261116_v002.xlsx
```

Not all elements are necessary for every file. Choose the information
that is most relevant to your project.

## Dates

Use the international date format:

`YYYYMMDD`

Examples:

-   `20261117` --- 17 November 2026
-   `20261117_experiment01.csv`
-   `20261117_sample_collection.xlsx`

This format ensures that files are sorted chronologically.

## Version control

Use sequential version numbers with leading zeros when different
versions of a document or dataset need to be retained:

``` text
sample_metadata_v001.xlsx
sample_metadata_v002.xlsx
sample_metadata_v003.xlsx
```

Avoid using terms such as:

-   `final`
-   `final_final`
-   `final_revised`
-   `new_version`

Whenever possible, use version control systems such as Git for scripts
and other text-based files.
