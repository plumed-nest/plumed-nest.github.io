**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmpptgkbjq6m:10657] *** Process received signal ***
[pkrvmpptgkbjq6m:10657] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10657] Signal code:  (-6)
[pkrvmpptgkbjq6m:10657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2dbfc45330]
[pkrvmpptgkbjq6m:10657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2dbfc9eb2c]
[pkrvmpptgkbjq6m:10657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2dbfc4527e]
[pkrvmpptgkbjq6m:10657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2dbfc288ff]
[pkrvmpptgkbjq6m:10657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2dc00a5ff5]
[pkrvmpptgkbjq6m:10657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2dc00bb0da]
[pkrvmpptgkbjq6m:10657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2dc00a5a55]
[pkrvmpptgkbjq6m:10657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2dc00a5a6f]
[pkrvmpptgkbjq6m:10657] [ 8] plumed_master(+0x146dd)[0x55f518ffe6dd]
[pkrvmpptgkbjq6m:10657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2dbfc2a1ca]
[pkrvmpptgkbjq6m:10657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2dbfc2a28b]
[pkrvmpptgkbjq6m:10657] [11] plumed_master(+0x15365)[0x55f518fff365]
[pkrvmpptgkbjq6m:10657] *** End of error message ***
</pre>
{% endraw %}
