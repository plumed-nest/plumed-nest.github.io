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
[runnervmeorf1:04366] *** Process received signal ***
[runnervmeorf1:04366] Signal: Aborted (6)
[runnervmeorf1:04366] Signal code:  (-6)
[runnervmeorf1:04366] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa54645330]
[runnervmeorf1:04366] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa5469eb2c]
[runnervmeorf1:04366] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa5464527e]
[runnervmeorf1:04366] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa546288ff]
[runnervmeorf1:04366] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa54aa5ff5]
[runnervmeorf1:04366] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa54abb0da]
[runnervmeorf1:04366] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa54aa5a55]
[runnervmeorf1:04366] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa54aa5a6f]
[runnervmeorf1:04366] [ 8] plumed_master(+0x146dd)[0x564c96af36dd]
[runnervmeorf1:04366] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa5462a1ca]
[runnervmeorf1:04366] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa5462a28b]
[runnervmeorf1:04366] [11] plumed_master(+0x15365)[0x564c96af4365]
[runnervmeorf1:04366] *** End of error message ***
</pre>
{% endraw %}
