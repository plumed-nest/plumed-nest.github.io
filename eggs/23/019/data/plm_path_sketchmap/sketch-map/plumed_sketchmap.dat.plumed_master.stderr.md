**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1370-99:61715] *** Process received signal ***
[fv-az1370-99:61715] Signal: Aborted (6)
[fv-az1370-99:61715] Signal code:  (-6)
[fv-az1370-99:61715] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d55245330]
[fv-az1370-99:61715] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d5529eb2c]
[fv-az1370-99:61715] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d5524527e]
[fv-az1370-99:61715] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d552288ff]
[fv-az1370-99:61715] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d556a5ff5]
[fv-az1370-99:61715] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d556bb0da]
[fv-az1370-99:61715] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d556a5a55]
[fv-az1370-99:61715] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d556a5a6f]
[fv-az1370-99:61715] [ 8] plumed_master(+0x146dd)[0x557b076ff6dd]
[fv-az1370-99:61715] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d5522a1ca]
[fv-az1370-99:61715] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d5522a28b]
[fv-az1370-99:61715] [11] plumed_master(+0x15365)[0x557b07700365]
[fv-az1370-99:61715] *** End of error message ***
</pre>
{% endraw %}
