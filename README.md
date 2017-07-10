**Note**: it is currently not working because gitit is missing a flag like pandoc's `embed_data_files`. So when gitit runs it will try to look for the data files in a predefined path (when building gitit in Travis).

This mimics what pandoc-nightly does for pandoc and replicate it to gitit. See https://github.com/pandoc-extras/pandoc-nightly/ for the details.
