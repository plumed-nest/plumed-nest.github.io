**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @37 : keyword ARG is compulsory for this action
[runnervmeorf1:09500] *** Process received signal ***
[runnervmeorf1:09500] Signal: Aborted (6)
[runnervmeorf1:09500] Signal code:  (-6)
[runnervmeorf1:09500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8db6245330]
[runnervmeorf1:09500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8db629eb2c]
[runnervmeorf1:09500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8db624527e]
[runnervmeorf1:09500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8db62288ff]
[runnervmeorf1:09500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8db66a5ff5]
[runnervmeorf1:09500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8db66bb0da]
[runnervmeorf1:09500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8db66a5a55]
[runnervmeorf1:09500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8db66a5a6f]
[runnervmeorf1:09500] [ 8] plumed_master(+0x146dd)[0x5587fbff96dd]
[runnervmeorf1:09500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8db622a1ca]
[runnervmeorf1:09500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8db622a28b]
[runnervmeorf1:09500] [11] plumed_master(+0x15365)[0x5587fbffa365]
[runnervmeorf1:09500] *** End of error message ***
</pre>
{% endraw %}
