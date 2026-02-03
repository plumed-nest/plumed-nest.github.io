**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmkj6or:04326] *** Process received signal ***
[runnervmkj6or:04326] Signal: Aborted (6)
[runnervmkj6or:04326] Signal code:  (-6)
[runnervmkj6or:04326] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b0da45330]
[runnervmkj6or:04326] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b0da9eb2c]
[runnervmkj6or:04326] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b0da4527e]
[runnervmkj6or:04326] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b0da288ff]
[runnervmkj6or:04326] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b0dea5ff5]
[runnervmkj6or:04326] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b0debb0da]
[runnervmkj6or:04326] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b0dea5a55]
[runnervmkj6or:04326] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b0dea5a6f]
[runnervmkj6or:04326] [ 8] plumed_master(+0x146dd)[0x562132bca6dd]
[runnervmkj6or:04326] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b0da2a1ca]
[runnervmkj6or:04326] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b0da2a28b]
[runnervmkj6or:04326] [11] plumed_master(+0x15365)[0x562132bcb365]
[runnervmkj6or:04326] *** End of error message ***
</pre>
{% endraw %}
