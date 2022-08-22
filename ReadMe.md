This is the code to download any file from colab, just replace the file name in place of *filename.extension*. Remember to add extension with the name

    try:
      from google.colab import files
      files.download('filename.extension')
    except Exception:
      pass
