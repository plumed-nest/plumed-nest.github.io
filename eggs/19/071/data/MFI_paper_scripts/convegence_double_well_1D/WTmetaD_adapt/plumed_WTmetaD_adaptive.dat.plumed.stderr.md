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
[runnervmeorf1:12183] *** Process received signal ***
[runnervmeorf1:12183] Signal: Aborted (6)
[runnervmeorf1:12183] Signal code:  (-6)
[runnervmeorf1:12183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe85ac45330]
[runnervmeorf1:12183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe85ac9eb2c]
[runnervmeorf1:12183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe85ac4527e]
[runnervmeorf1:12183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe85ac288ff]
[runnervmeorf1:12183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe85b0a5ff5]
[runnervmeorf1:12183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe85b0bb0da]
[runnervmeorf1:12183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe85b0a5a55]
[runnervmeorf1:12183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe85b0a5a6f]
[runnervmeorf1:12183] [ 8] plumed(+0x146dd)[0x5650bd9476dd]
[runnervmeorf1:12183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe85ac2a1ca]
[runnervmeorf1:12183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe85ac2a28b]
[runnervmeorf1:12183] [11] plumed(+0x15365)[0x5650bd948365]
[runnervmeorf1:12183] *** End of error message ***
</pre>
{% endraw %}
