# SIMH v3.12
### The Computer History Simulation Project 

Current Official version:  v3.12-3  (announced 2022.12.12)

## This is a copy of *SIMH v3.12-3* from Bob Supnik's web site.

It is downloaded here to allow you to fork / clone for your own personal development.

You are highly encouraged to visit https://simh.trailing-edge.com as there is trove of useful
information and code there.

---

## From the simh.trailing-edge.com site:


### Simulators

SIMH is a highly portable, multi-system simulator.

SIMH implements simulators for:

-    Data General Nova, Eclipse
-    Digital Equipment Corporation PDP-1, PDP-4, PDP-7, PDP-8, PDP-9, PDP-10, PDP-11, PDP-15 (and UC15), VAX11/780, VAX3900
-    GRI Corporation GRI-909, GRI-99
-    IBM 1401, 1620, 7090/7094, System 3
-    Interdata (Perkin-Elmer) 16b and 32b systems
-    Hewlett-Packard 2114, 2115, 2116, 2100, 21MX, 1000, 3000
-    Honeywell H316/H516
-    MITS Altair 8800, 8080 only
-    Royal-Mcbee LGP-30, LGP-21
-    Scientific Data Systems SDS 940
-    Xerox Data Systems Sigma 32b systems 

Also available is a collection of tools for manipulating simulator file formats and for cross-assembling code for the PDP-1, PDP-7, PDP-8, and PDP-11. 

### Release Notes for V3.12-3

This release is mostly bug fixes, particularly in the PDP-11 and Sigma simulators. Support for running SimH on MacOS "Classic" (pre-OSX) and OS/2 has been dropped. See the detailed revision histories in individual source code modules for details. 

### Release Notes for V3.12-2
This is the first official release of SimH 3.X in more than two years. It includes numerous bug fixes and extensions to the individual simulators, as well as a few major upgrades in capability:

-    The magtape library (sim_tape.c) has been extended to allow the inclusion of private metadata in SimH format tapes. The extension is backward compatible to the previous format and is invisible to simulators that do not need or support private metadata.
-    To support the tape format extension, there is a new version of the mtdump utility. In addition to supporting the extended SimH tape format, it supports P7B (Pierce 7bit) format for the first time.
-    Support for non-standard C compliant compilers has been dropped. 

See the detailed revision history in *sim_rev.h* for more details. 
