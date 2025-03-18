# picoCTF-writeup

## FANTASY CTF: 
Open a shell with the command nc verbal-sleep.picoctf.net 55716, when prompted use option C (register a single private account) then option A (play the game) later.

picoCTF{m1113n1um_3d1710n_fc649bc5}

## Rust fixme 1: 
Open code in editor and run debugger. "let key = String::from("CSUCKS")" should have a ; at the end of it. 

"if res.is_err() {
    ret;
}" 

Should be return instead of ret

"println!(
    ":?",
    String::from_utf8_lossy(&decrypted_buffer)
);"

Should be {} instead of :?

picoCTF{4r3_y0u_4_ru$t4c30n_n0w?}

Once you edit those, run it again and it'll give flag.

## Big Zip: 
Unzip the file and search through all text files for a flag. I did this by going to Windows Explorer and typing in the search bar "Content: picoCTF"

picoCTF{gr3p_15_m4g1c_ef8790dc}
