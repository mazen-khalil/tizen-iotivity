# Iotivity for Tizen (Iotcon)

### Recomended tool to use:
https://github.com/cabo/cbor-diag

### CBOR >> Diagnostic Notation
``$ cbor2diag.rb server.dat > server.diag``

### Diagnostic Notation >> CBOR
``$ diag2cbor.rb server.diag > server.dat``

### To validate and convert between Diagnostic Notation and hexdump (byte)
http://cbor.me/

### CBOR >> Hexdump (byte)
``$ cbor2pretty.rb server.dat > server.hex`` / ``$ xxd -p server.dat > server.hex``

### Hexdump (byte) >> CBOR
``$ pretty2cbor.rb server.hex > server.dat`` / ``$ xxd -r -p server.hex > server.dat``
