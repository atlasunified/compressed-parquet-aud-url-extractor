# compressed-parquet-aud-url-extractor

This Python script reads data from a Parquet file, processes it, and extracts audio URLs based on user-selected columns. The user can select columns by entering column numbers as a comma-separated list (e.g., '1, 2, 3') or a range (e.g., '1-3'). After selecting the desired columns, the script filters out audio URLs in the '.mp3', '.wav', '.ogg', '.flac', and '.aac' formats. It then deduplicates the extracted audio URLs and saves them in a text file called 'myaudiolist.txt', with each URL on a separate line. The primary purpose of this script is to help users easily extract and organize audio URLs from a given Parquet file.
