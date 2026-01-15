**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmmtnos:34251] *** Process received signal ***
[runnervmmtnos:34251] Signal: Aborted (6)
[runnervmmtnos:34251] Signal code:  (-6)
[runnervmmtnos:34251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f96ed845330]
[runnervmmtnos:34251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f96ed89eb2c]
[runnervmmtnos:34251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f96ed84527e]
[runnervmmtnos:34251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96ed8288ff]
[runnervmmtnos:34251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96edca5ff5]
[runnervmmtnos:34251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96edcbb0da]
[runnervmmtnos:34251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96edca5a55]
[runnervmmtnos:34251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96edca5a6f]
[runnervmmtnos:34251] [ 8] plumed_master(+0x146dd)[0x55bd717816dd]
[runnervmmtnos:34251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f96ed82a1ca]
[runnervmmtnos:34251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f96ed82a28b]
[runnervmmtnos:34251] [11] plumed_master(+0x15365)[0x55bd71782365]
[runnervmmtnos:34251] *** End of error message ***
</pre>
{% endraw %}
