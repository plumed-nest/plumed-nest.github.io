**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az1047-397:62954] *** Process received signal ***
[fv-az1047-397:62954] Signal: Aborted (6)
[fv-az1047-397:62954] Signal code:  (-6)
[fv-az1047-397:62954] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d6a845330]
[fv-az1047-397:62954] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d6a89eb2c]
[fv-az1047-397:62954] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d6a84527e]
[fv-az1047-397:62954] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d6a8288ff]
[fv-az1047-397:62954] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d6aca5ff5]
[fv-az1047-397:62954] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d6acbb0da]
[fv-az1047-397:62954] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d6aca5a55]
[fv-az1047-397:62954] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d6aca5a6f]
[fv-az1047-397:62954] [ 8] plumed(+0x146dd)[0x5627ae14e6dd]
[fv-az1047-397:62954] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d6a82a1ca]
[fv-az1047-397:62954] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d6a82a28b]
[fv-az1047-397:62954] [11] plumed(+0x15365)[0x5627ae14f365]
[fv-az1047-397:62954] *** End of error message ***
</pre>
{% endraw %}
