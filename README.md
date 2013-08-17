WoP-Pandora
===========

Word of Padman for OpenPandora (featuring ARM support and GLES renderer)

OpenPandora
===========

This fork is aimed at OpenPandra, so get:
 * ARM compatibilty (using -DARM)
 * Some NEON optimized code (using -DNEON)
 * GLES renderer (using -DHAVE_GLES)
 * Toggle Crouch function (using -DCROUCH), disabled by default, with a new variable in cfg to activate
 * OpenPandora support of course (using -DPANDORA), for screen resolution mainly.
 
For the Pandora version, I used some Hardwired modif in the Makefile (COMPILE_PLATFORM=pandora and COMPILE_ARCH=arm)

For more info on the OpenPandora go here: http://boards.openpandora.org/
Specific thread for Jedi Academy on the OpenPandora here: http://boards.openpandora.org/index.php/topic/14047-world-of-padman/
