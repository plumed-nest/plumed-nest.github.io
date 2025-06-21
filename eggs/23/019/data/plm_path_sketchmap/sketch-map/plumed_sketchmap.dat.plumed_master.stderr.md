**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:08381] *** Process received signal ***
[pkrvmxyh4eaekms:08381] Signal: Aborted (6)
[pkrvmxyh4eaekms:08381] Signal code:  (-6)
[pkrvmxyh4eaekms:08381] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f90e5645330]
[pkrvmxyh4eaekms:08381] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f90e569eb2c]
[pkrvmxyh4eaekms:08381] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f90e564527e]
[pkrvmxyh4eaekms:08381] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90e56288ff]
[pkrvmxyh4eaekms:08381] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90e5aa5ff5]
[pkrvmxyh4eaekms:08381] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90e5abb0da]
[pkrvmxyh4eaekms:08381] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90e5aa5a55]
[pkrvmxyh4eaekms:08381] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90e5aa5a6f]
[pkrvmxyh4eaekms:08381] [ 8] plumed_master(+0x146dd)[0x5653822966dd]
[pkrvmxyh4eaekms:08381] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f90e562a1ca]
[pkrvmxyh4eaekms:08381] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f90e562a28b]
[pkrvmxyh4eaekms:08381] [11] plumed_master(+0x15365)[0x565382297365]
[pkrvmxyh4eaekms:08381] *** End of error message ***
</pre>
{% endraw %}
