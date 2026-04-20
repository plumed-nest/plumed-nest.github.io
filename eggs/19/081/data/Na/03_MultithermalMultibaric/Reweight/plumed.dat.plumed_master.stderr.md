**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmeorf1:11209] *** Process received signal ***
[runnervmeorf1:11209] Signal: Aborted (6)
[runnervmeorf1:11209] Signal code:  (-6)
[runnervmeorf1:11209] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b0ea45330]
[runnervmeorf1:11209] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b0ea9eb2c]
[runnervmeorf1:11209] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b0ea4527e]
[runnervmeorf1:11209] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b0ea288ff]
[runnervmeorf1:11209] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b0eea5ff5]
[runnervmeorf1:11209] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b0eebb0da]
[runnervmeorf1:11209] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b0eea5a55]
[runnervmeorf1:11209] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b0eea5a6f]
[runnervmeorf1:11209] [ 8] plumed_master(+0x146dd)[0x55cfb02fa6dd]
[runnervmeorf1:11209] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b0ea2a1ca]
[runnervmeorf1:11209] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b0ea2a28b]
[runnervmeorf1:11209] [11] plumed_master(+0x15365)[0x55cfb02fb365]
[runnervmeorf1:11209] *** End of error message ***
</pre>
{% endraw %}
