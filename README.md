CellWire is an implementation of 3gpp EPC(MME, SGW, PGW, HSS)

The implemntation consists in several components:
  - lib/core : the library contains the core of the framework.
      memory pool, thread, lock, timer, ...

  - lib/logger : the logging library

  - lib/s1ap : the S1AP message encoding/decoding library

  - lib/nas : the NAS message encoding/decoding library

  - lib/s6a : the freeDiameter wrapper for S6A

  - lib/gtp : the GTPv2-C/GTP-U message encoding/decoding library

  - src/mme : the heart of MME protocol stack

  - src/hss : the heart of HSS protocol stack


See LICENSE file for legal information on this software.

See INSTALL for information on building and using this software.