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
[runnervmkj6or:12664] *** Process received signal ***
[runnervmkj6or:12664] Signal: Aborted (6)
[runnervmkj6or:12664] Signal code:  (-6)
[runnervmkj6or:12664] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2626645330]
[runnervmkj6or:12664] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f262669eb2c]
[runnervmkj6or:12664] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f262664527e]
[runnervmkj6or:12664] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26266288ff]
[runnervmkj6or:12664] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2626aa5ff5]
[runnervmkj6or:12664] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2626abb0da]
[runnervmkj6or:12664] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2626aa5a55]
[runnervmkj6or:12664] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2626aa5a6f]
[runnervmkj6or:12664] [ 8] plumed(+0x146dd)[0x5581918866dd]
[runnervmkj6or:12664] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f262662a1ca]
[runnervmkj6or:12664] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f262662a28b]
[runnervmkj6or:12664] [11] plumed(+0x15365)[0x558191887365]
[runnervmkj6or:12664] *** End of error message ***
</pre>
{% endraw %}
