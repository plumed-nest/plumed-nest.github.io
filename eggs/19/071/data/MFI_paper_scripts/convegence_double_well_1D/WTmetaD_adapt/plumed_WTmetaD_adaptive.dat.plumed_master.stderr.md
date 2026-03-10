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
[runnervm0kj6c:12164] *** Process received signal ***
[runnervm0kj6c:12164] Signal: Aborted (6)
[runnervm0kj6c:12164] Signal code:  (-6)
[runnervm0kj6c:12164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f270c245330]
[runnervm0kj6c:12164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f270c29eb2c]
[runnervm0kj6c:12164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f270c24527e]
[runnervm0kj6c:12164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f270c2288ff]
[runnervm0kj6c:12164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f270c6a5ff5]
[runnervm0kj6c:12164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f270c6bb0da]
[runnervm0kj6c:12164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f270c6a5a55]
[runnervm0kj6c:12164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f270c6a5a6f]
[runnervm0kj6c:12164] [ 8] plumed_master(+0x146dd)[0x560963d1a6dd]
[runnervm0kj6c:12164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f270c22a1ca]
[runnervm0kj6c:12164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f270c22a28b]
[runnervm0kj6c:12164] [11] plumed_master(+0x15365)[0x560963d1b365]
[runnervm0kj6c:12164] *** End of error message ***
</pre>
{% endraw %}
