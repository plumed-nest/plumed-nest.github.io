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
[fv-az1047-397:65839] *** Process received signal ***
[fv-az1047-397:65839] Signal: Aborted (6)
[fv-az1047-397:65839] Signal code:  (-6)
[fv-az1047-397:65839] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca6f245330]
[fv-az1047-397:65839] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca6f29eb2c]
[fv-az1047-397:65839] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca6f24527e]
[fv-az1047-397:65839] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca6f2288ff]
[fv-az1047-397:65839] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca6f6a5ff5]
[fv-az1047-397:65839] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca6f6bb0da]
[fv-az1047-397:65839] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca6f6a5a55]
[fv-az1047-397:65839] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca6f6a5a6f]
[fv-az1047-397:65839] [ 8] plumed(+0x146dd)[0x55a8f10056dd]
[fv-az1047-397:65839] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca6f22a1ca]
[fv-az1047-397:65839] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca6f22a28b]
[fv-az1047-397:65839] [11] plumed(+0x15365)[0x55a8f1006365]
[fv-az1047-397:65839] *** End of error message ***
</pre>
{% endraw %}
