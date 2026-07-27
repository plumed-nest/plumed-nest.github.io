**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmvrwv9:10169] *** Process received signal ***
[runnervmvrwv9:10169] Signal: Aborted (6)
[runnervmvrwv9:10169] Signal code:  (-6)
[runnervmvrwv9:10169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8b4845330]
[runnervmvrwv9:10169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8b489eb2c]
[runnervmvrwv9:10169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8b484527e]
[runnervmvrwv9:10169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8b48288ff]
[runnervmvrwv9:10169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8b4ca5ff5]
[runnervmvrwv9:10169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8b4cbb0da]
[runnervmvrwv9:10169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8b4ca5a55]
[runnervmvrwv9:10169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8b4ca5a6f]
[runnervmvrwv9:10169] [ 8] plumed(+0x146dd)[0x5559e01616dd]
[runnervmvrwv9:10169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8b482a1ca]
[runnervmvrwv9:10169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8b482a28b]
[runnervmvrwv9:10169] [11] plumed(+0x15365)[0x5559e0162365]
[runnervmvrwv9:10169] *** End of error message ***
</pre>
{% endraw %}
