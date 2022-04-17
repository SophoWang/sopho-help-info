vhdlan help
===========

::
    
    Usage: vhdlan [options] filename(s) 
    
    Summary of vhdlan Options: 
    --------------------------
    -help             [off]
       Print usage information for vhdlan and exits.
    
    -v[ersion]        [off]
       Print version and exits.
    
    -nc               [off]
       Suppress copyright banner.
    
    -q                [off]
       Work in quiet mode.
    
    -verb[ose]        [off]
       List setup files and other detailed information.
    
    -vc_lic_wait mins [off]
       Specify waiting time in minutes for license checkout (only VC build).
    
    -licw[ait] mins   [off]
       Specify waiting time in minutes for license checkout.
    
    -event            [on]
        Perform VHDL analysis.
    
    -w[ork] library   [off]
       Map a design library name to the logical library name WORK, which receives 
       the output of the analyzer.
    
    -vhdl87           [off]
       Enable backward compatibility for VHDL-87 syntax rules.
       VHDL-93 syntax rules are the default.
    
    -o[utput] outfile [off]
       Redirect all output to outfile.
    
    -l[og]    outfile [off]
       Redirect all output to outfile.
    
    -li[st]           [off]
       Create a list file (.lis) containing the VHDL source,the names of the 
       analyzed design units, and  warning or error messages produced during the 
       analysis.
    
    -no_op[timize]    [off]
       Enable runtime checking by disabling various event optimizations.
       Using this option will slow simulation performance.
    
    -xlrm             [off]
       Enable vhdl features beyond those described in lrm.
    
    -f[ile] optionsfile      [off]
       Expand command line options from file optionsfile.
    
    -functional_vital [off]
       Remove timing information from VITAL cells. Better simulation performance 
       can be expected by using -functional_vital instead of -novitaltiming during 
       simulation.
    
    -psl              [off]
       Enable psl assertions
    
    -pslfile pslfile         [off]
       specify psl assertion file pslfile
    
    -pslhide          [off]
       to hide psl symbols
    
    -full64           [off]
       Analyze the design for 64-bit simulation.
    
    -vhdl08           [off]
       Enable support for VHDL 2008 constructs.
    
    -kdb              [off]
       Generate Verdi KDB database.
    
    -gen_sv_pkg
        Translate VHDL types and constants in a package to its equivalent SystemVerilog equivalent.  By default, translated package is left in working directory.
    
    -gen_sv_pkg_dir=dir
        Override default directory in which to leave translated package when -gen_sv_pkg is given.
    
