# gem

**gem** is a Linux CLI for GnuPG string encryption
    
    gme "cleartext" [pub_key_file_name] [pub_key_file_path]

<br>
    
**gem** can also be imported as a Python module

    import gem
    
    encrypted_str = gem.main(clear_text, 
                             pubkey_file_name='pubkey.asc', 
                             pubkey_file_path='/home/dd/Documents/pubkeys/')
   (rename or copy the file `gem` to `gem.py` before importing)


Finally, **gem** can also take piped string input at the command-line

    echo "Hello" | gem
    
when called without arguments, **gem** takes input from the keyboard

    gem
    
(end keyboard input with CTRL-D)

<br>

# cle

**cle** encrypts the clipboard content in place

    cle
    
(custom keyboard shortcut execution highly recommended)
