**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmeorf1:04479] *** Process received signal ***
[runnervmeorf1:04479] Signal: Aborted (6)
[runnervmeorf1:04479] Signal code:  (-6)
[runnervmeorf1:04479] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34ba245330]
[runnervmeorf1:04479] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34ba29eb2c]
[runnervmeorf1:04479] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34ba24527e]
[runnervmeorf1:04479] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34ba2288ff]
[runnervmeorf1:04479] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34ba6a5ff5]
[runnervmeorf1:04479] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34ba6bb0da]
[runnervmeorf1:04479] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34ba6a5a55]
[runnervmeorf1:04479] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34ba6a5a6f]
[runnervmeorf1:04479] [ 8] plumed_master(+0x146dd)[0x55f532fe36dd]
[runnervmeorf1:04479] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34ba22a1ca]
[runnervmeorf1:04479] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34ba22a28b]
[runnervmeorf1:04479] [11] plumed_master(+0x15365)[0x55f532fe4365]
[runnervmeorf1:04479] *** End of error message ***
</pre>
{% endraw %}
