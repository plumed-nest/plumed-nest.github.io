**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmkj6or:07279] *** Process received signal ***
[runnervmkj6or:07279] Signal: Aborted (6)
[runnervmkj6or:07279] Signal code:  (-6)
[runnervmkj6or:07279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e01045330]
[runnervmkj6or:07279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e0109eb2c]
[runnervmkj6or:07279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e0104527e]
[runnervmkj6or:07279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e010288ff]
[runnervmkj6or:07279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e014a5ff5]
[runnervmkj6or:07279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e014bb0da]
[runnervmkj6or:07279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e014a5a55]
[runnervmkj6or:07279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e014a5a6f]
[runnervmkj6or:07279] [ 8] plumed_master(+0x146dd)[0x55de99b166dd]
[runnervmkj6or:07279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e0102a1ca]
[runnervmkj6or:07279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e0102a28b]
[runnervmkj6or:07279] [11] plumed_master(+0x15365)[0x55de99b17365]
[runnervmkj6or:07279] *** End of error message ***
</pre>
{% endraw %}
