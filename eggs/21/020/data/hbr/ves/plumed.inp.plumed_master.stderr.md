**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmmtnos:34289] *** Process received signal ***
[runnervmmtnos:34289] Signal: Aborted (6)
[runnervmmtnos:34289] Signal code:  (-6)
[runnervmmtnos:34289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd48c45330]
[runnervmmtnos:34289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd48c9eb2c]
[runnervmmtnos:34289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd48c4527e]
[runnervmmtnos:34289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd48c288ff]
[runnervmmtnos:34289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd490a5ff5]
[runnervmmtnos:34289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd490bb0da]
[runnervmmtnos:34289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd490a5a55]
[runnervmmtnos:34289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd490a5a6f]
[runnervmmtnos:34289] [ 8] plumed_master(+0x146dd)[0x564fc1aed6dd]
[runnervmmtnos:34289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd48c2a1ca]
[runnervmmtnos:34289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd48c2a28b]
[runnervmmtnos:34289] [11] plumed_master(+0x15365)[0x564fc1aee365]
[runnervmmtnos:34289] *** End of error message ***
</pre>
{% endraw %}
