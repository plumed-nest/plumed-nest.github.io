**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmeorf1:12199] *** Process received signal ***
[runnervmeorf1:12199] Signal: Aborted (6)
[runnervmeorf1:12199] Signal code:  (-6)
[runnervmeorf1:12199] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa69ec45330]
[runnervmeorf1:12199] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa69ec9eb2c]
[runnervmeorf1:12199] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa69ec4527e]
[runnervmeorf1:12199] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa69ec288ff]
[runnervmeorf1:12199] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa69f0a5ff5]
[runnervmeorf1:12199] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa69f0bb0da]
[runnervmeorf1:12199] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa69f0a5a55]
[runnervmeorf1:12199] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa69f0a5a6f]
[runnervmeorf1:12199] [ 8] plumed_master(+0x146dd)[0x55afe8e536dd]
[runnervmeorf1:12199] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa69ec2a1ca]
[runnervmeorf1:12199] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa69ec2a28b]
[runnervmeorf1:12199] [11] plumed_master(+0x15365)[0x55afe8e54365]
[runnervmeorf1:12199] *** End of error message ***
</pre>
{% endraw %}
