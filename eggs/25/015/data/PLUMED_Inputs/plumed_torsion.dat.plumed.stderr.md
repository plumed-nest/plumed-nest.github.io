**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmmklqx:04962] *** Process received signal ***
[runnervmmklqx:04962] Signal: Aborted (6)
[runnervmmklqx:04962] Signal code:  (-6)
[runnervmmklqx:04962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02ce645330]
[runnervmmklqx:04962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02ce69eb2c]
[runnervmmklqx:04962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02ce64527e]
[runnervmmklqx:04962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02ce6288ff]
[runnervmmklqx:04962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02ceaa5ff5]
[runnervmmklqx:04962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02ceabb0da]
[runnervmmklqx:04962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02ceaa5a55]
[runnervmmklqx:04962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02ceaa5a6f]
[runnervmmklqx:04962] [ 8] plumed(+0x146dd)[0x5645654dc6dd]
[runnervmmklqx:04962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02ce62a1ca]
[runnervmmklqx:04962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02ce62a28b]
[runnervmmklqx:04962] [11] plumed(+0x15365)[0x5645654dd365]
[runnervmmklqx:04962] *** End of error message ***
</pre>
{% endraw %}
