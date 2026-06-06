Challenge Title: `Neural Oracle`<br>
Author: `nmluan`<br>

Description:<br>
BASIX-7 is an autonomous authentication system protecting a classified
research network. It accepts a 40-byte passphrase and runs it through an
internal neural network validator before granting access. Conventional
reverse engineering has failed: the binary contains no string comparisons,
no hash checks, and no plaintext secrets.<br>

Extract the model, understand it, and produce the input that
makes it output 1.0.<br>

Distributed file: oracle.bin