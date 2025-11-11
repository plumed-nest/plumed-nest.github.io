**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmw9dnm:06159] *** Process received signal ***
[runnervmw9dnm:06159] Signal: Aborted (6)
[runnervmw9dnm:06159] Signal code:  (-6)
[runnervmw9dnm:06159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8007645330]
[runnervmw9dnm:06159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f800769eb2c]
[runnervmw9dnm:06159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f800764527e]
[runnervmw9dnm:06159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80076288ff]
[runnervmw9dnm:06159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8007aa5ff5]
[runnervmw9dnm:06159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8007abb0da]
[runnervmw9dnm:06159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8007aa5a55]
[runnervmw9dnm:06159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8007aa5a6f]
[runnervmw9dnm:06159] [ 8] plumed_master(+0x146dd)[0x55cf3daba6dd]
[runnervmw9dnm:06159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f800762a1ca]
[runnervmw9dnm:06159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f800762a28b]
[runnervmw9dnm:06159] [11] plumed_master(+0x15365)[0x55cf3dabb365]
[runnervmw9dnm:06159] *** End of error message ***
</pre>
{% endraw %}
