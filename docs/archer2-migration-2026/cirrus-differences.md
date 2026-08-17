# Main similarities/differences between Cirrus NCR and ARCHER2

This section provides an overview of the main differences between
the ARCHER2 system and Cirrus NCR along with links to more
information where appropriate.

## Similarities

- Cirrus NCR is an HPE Cray EX system like ARCHER2
- Cirrus NCR provides the HPE Cray Programming Environment (CPE)
  in a similar way to ARCHER2 so many of the same libraries, tools
  and compilers are available (though they are more recent versions
  on Cirrus)


## Hardware

- Cirrus is a much smaller system - there are only 640 compute nodes on Cirrus
  (compared to 5860 on ARCHER2)
- There are **no** GPU nodes on Cirrus NCR
- There are 288 cores on a Cirrus NCR compute node rather than 128 on ARCHER2
- Cirrus NCR uses the HPE Cray Slingshot 11 interconnect rather than the 
  Slingshot 10 interconnect used on ARCHER2
- Cirrus NCR compute nodes can access the internet directly
- There are no separate "serial" nodes
- For more information see [the Hardware section in the User Guide](../user-guide/hardware.md)

## Software

- The software provided by the Cirrus support time is delivered via Spack rather
  than manual install processes used on ARCHER2
- We will typically advise that users use Spack to build their own software on 
  Cirrus NCR wherever possible
- A smaller number of research software packages are provided centrally on Cirrus
  compared to ARCHER2

## Slurm scheduler configuration

- Many of the partitions and QoS are similar between the two systems.
  See the [Scheduler secion of the User Guide](../user-guide/batch.md)


