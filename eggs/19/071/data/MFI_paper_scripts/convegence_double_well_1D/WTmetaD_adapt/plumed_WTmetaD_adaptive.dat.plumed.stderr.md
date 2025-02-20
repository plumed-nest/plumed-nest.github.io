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
[fv-az1720-841:10726] *** Process received signal ***
[fv-az1720-841:10726] Signal: Aborted (6)
[fv-az1720-841:10726] Signal code:  (-6)
[fv-az1720-841:10726] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a46245330]
[fv-az1720-841:10726] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a4629eb2c]
[fv-az1720-841:10726] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a4624527e]
[fv-az1720-841:10726] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a462288ff]
[fv-az1720-841:10726] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a466a5ff5]
[fv-az1720-841:10726] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a466bb0da]
[fv-az1720-841:10726] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a466a5a55]
[fv-az1720-841:10726] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a466a5a6f]
[fv-az1720-841:10726] [ 8] plumed(+0x146dd)[0x55f4bf06e6dd]
[fv-az1720-841:10726] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a4622a1ca]
[fv-az1720-841:10726] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a4622a28b]
[fv-az1720-841:10726] [11] plumed(+0x15365)[0x55f4bf06f365]
[fv-az1720-841:10726] *** End of error message ***
</pre>
{% endraw %}
