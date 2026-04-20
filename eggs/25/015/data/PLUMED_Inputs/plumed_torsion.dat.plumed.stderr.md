**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmeorf1:04350] *** Process received signal ***
[runnervmeorf1:04350] Signal: Aborted (6)
[runnervmeorf1:04350] Signal code:  (-6)
[runnervmeorf1:04350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f481b845330]
[runnervmeorf1:04350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f481b89eb2c]
[runnervmeorf1:04350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f481b84527e]
[runnervmeorf1:04350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f481b8288ff]
[runnervmeorf1:04350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f481bca5ff5]
[runnervmeorf1:04350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f481bcbb0da]
[runnervmeorf1:04350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f481bca5a55]
[runnervmeorf1:04350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f481bca5a6f]
[runnervmeorf1:04350] [ 8] plumed(+0x146dd)[0x56513599e6dd]
[runnervmeorf1:04350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f481b82a1ca]
[runnervmeorf1:04350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f481b82a28b]
[runnervmeorf1:04350] [11] plumed(+0x15365)[0x56513599f365]
[runnervmeorf1:04350] *** End of error message ***
</pre>
{% endraw %}
