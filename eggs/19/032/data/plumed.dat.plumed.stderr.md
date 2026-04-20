**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervmeorf1:11270] *** Process received signal ***
[runnervmeorf1:11270] Signal: Aborted (6)
[runnervmeorf1:11270] Signal code:  (-6)
[runnervmeorf1:11270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fccc5845330]
[runnervmeorf1:11270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fccc589eb2c]
[runnervmeorf1:11270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fccc584527e]
[runnervmeorf1:11270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fccc58288ff]
[runnervmeorf1:11270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fccc5ca5ff5]
[runnervmeorf1:11270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fccc5cbb0da]
[runnervmeorf1:11270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fccc5ca5a55]
[runnervmeorf1:11270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fccc5ca5a6f]
[runnervmeorf1:11270] [ 8] plumed(+0x146dd)[0x5603675ee6dd]
[runnervmeorf1:11270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fccc582a1ca]
[runnervmeorf1:11270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fccc582a28b]
[runnervmeorf1:11270] [11] plumed(+0x15365)[0x5603675ef365]
[runnervmeorf1:11270] *** End of error message ***
</pre>
{% endraw %}
