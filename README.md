# Iotivity for Tizen (Iotcon)

### Recomended tool to use:
https://github.com/cabo/cbor-diag

### CBOR >> Diagnostic Notation
<code>$ cbor2diag.rb server.dat > server.diag</code>


### Diagnostic Notation >> CBOR
<code>$ diag2cbor.rb server.diag > server.dat</code>

### To validate and convert between Diagnostic Notation and hexdump (byte)
http://cbor.me/

### CBOR >> Hexdump (byte)
<code>$ xxd -p server.dat > server.hex</code>

### Hexdump (byte) >> CBOR
<code>$ xxd -r -p server.hex > server.dat</code>


