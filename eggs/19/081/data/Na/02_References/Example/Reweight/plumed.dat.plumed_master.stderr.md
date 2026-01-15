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
[runnervmmtnos:38530] *** Process received signal ***
[runnervmmtnos:38530] Signal: Aborted (6)
[runnervmmtnos:38530] Signal code:  (-6)
[runnervmmtnos:38530] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81bf445330]
[runnervmmtnos:38530] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81bf49eb2c]
[runnervmmtnos:38530] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81bf44527e]
[runnervmmtnos:38530] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81bf4288ff]
[runnervmmtnos:38530] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81bf8a5ff5]
[runnervmmtnos:38530] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81bf8bb0da]
[runnervmmtnos:38530] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81bf8a5a55]
[runnervmmtnos:38530] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81bf8a5a6f]
[runnervmmtnos:38530] [ 8] plumed_master(+0x146dd)[0x555be251f6dd]
[runnervmmtnos:38530] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81bf42a1ca]
[runnervmmtnos:38530] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81bf42a28b]
[runnervmmtnos:38530] [11] plumed_master(+0x15365)[0x555be2520365]
[runnervmmtnos:38530] *** End of error message ***
</pre>
{% endraw %}
