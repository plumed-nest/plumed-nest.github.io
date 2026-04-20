**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmeorf1:10999] *** Process received signal ***
[runnervmeorf1:10999] Signal: Aborted (6)
[runnervmeorf1:10999] Signal code:  (-6)
[runnervmeorf1:10999] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f09f0245330]
[runnervmeorf1:10999] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f09f029eb2c]
[runnervmeorf1:10999] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f09f024527e]
[runnervmeorf1:10999] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09f02288ff]
[runnervmeorf1:10999] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09f06a5ff5]
[runnervmeorf1:10999] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09f06bb0da]
[runnervmeorf1:10999] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09f06a5a55]
[runnervmeorf1:10999] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09f06a5a6f]
[runnervmeorf1:10999] [ 8] plumed_master(+0x146dd)[0x561a4d1d96dd]
[runnervmeorf1:10999] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f09f022a1ca]
[runnervmeorf1:10999] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f09f022a28b]
[runnervmeorf1:10999] [11] plumed_master(+0x15365)[0x561a4d1da365]
[runnervmeorf1:10999] *** End of error message ***
</pre>
{% endraw %}
