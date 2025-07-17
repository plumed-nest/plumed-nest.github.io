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
[pkrvmq0rgcvqdmg:12129] *** Process received signal ***
[pkrvmq0rgcvqdmg:12129] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12129] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12129] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad32445330]
[pkrvmq0rgcvqdmg:12129] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad3249eb2c]
[pkrvmq0rgcvqdmg:12129] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad3244527e]
[pkrvmq0rgcvqdmg:12129] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad324288ff]
[pkrvmq0rgcvqdmg:12129] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad328a5ff5]
[pkrvmq0rgcvqdmg:12129] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad328bb0da]
[pkrvmq0rgcvqdmg:12129] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad328a5a55]
[pkrvmq0rgcvqdmg:12129] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad328a5a6f]
[pkrvmq0rgcvqdmg:12129] [ 8] plumed(+0x146dd)[0x5610374cb6dd]
[pkrvmq0rgcvqdmg:12129] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad3242a1ca]
[pkrvmq0rgcvqdmg:12129] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad3242a28b]
[pkrvmq0rgcvqdmg:12129] [11] plumed(+0x15365)[0x5610374cc365]
[pkrvmq0rgcvqdmg:12129] *** End of error message ***
</pre>
{% endraw %}
