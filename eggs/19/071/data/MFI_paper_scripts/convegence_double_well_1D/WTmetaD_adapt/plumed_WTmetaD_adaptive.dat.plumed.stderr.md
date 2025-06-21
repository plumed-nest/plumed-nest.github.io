**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmxyh4eaekms:13292] *** Process received signal ***
[pkrvmxyh4eaekms:13292] Signal: Aborted (6)
[pkrvmxyh4eaekms:13292] Signal code:  (-6)
[pkrvmxyh4eaekms:13292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f869d645330]
[pkrvmxyh4eaekms:13292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f869d69eb2c]
[pkrvmxyh4eaekms:13292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f869d64527e]
[pkrvmxyh4eaekms:13292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f869d6288ff]
[pkrvmxyh4eaekms:13292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f869daa5ff5]
[pkrvmxyh4eaekms:13292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f869dabb0da]
[pkrvmxyh4eaekms:13292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f869daa5a55]
[pkrvmxyh4eaekms:13292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f869daa5a6f]
[pkrvmxyh4eaekms:13292] [ 8] plumed(+0x146dd)[0x556e954496dd]
[pkrvmxyh4eaekms:13292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f869d62a1ca]
[pkrvmxyh4eaekms:13292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f869d62a28b]
[pkrvmxyh4eaekms:13292] [11] plumed(+0x15365)[0x556e9544a365]
[pkrvmxyh4eaekms:13292] *** End of error message ***
</pre>
{% endraw %}
