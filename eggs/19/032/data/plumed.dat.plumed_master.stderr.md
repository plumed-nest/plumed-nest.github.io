**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervmmtnos:37802] *** Process received signal ***
[runnervmmtnos:37802] Signal: Aborted (6)
[runnervmmtnos:37802] Signal code:  (-6)
[runnervmmtnos:37802] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f44c0c45330]
[runnervmmtnos:37802] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f44c0c9eb2c]
[runnervmmtnos:37802] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f44c0c4527e]
[runnervmmtnos:37802] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44c0c288ff]
[runnervmmtnos:37802] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44c10a5ff5]
[runnervmmtnos:37802] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44c10bb0da]
[runnervmmtnos:37802] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44c10a5a55]
[runnervmmtnos:37802] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44c10a5a6f]
[runnervmmtnos:37802] [ 8] plumed_master(+0x146dd)[0x5632c75806dd]
[runnervmmtnos:37802] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f44c0c2a1ca]
[runnervmmtnos:37802] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f44c0c2a28b]
[runnervmmtnos:37802] [11] plumed_master(+0x15365)[0x5632c7581365]
[runnervmmtnos:37802] *** End of error message ***
</pre>
{% endraw %}
