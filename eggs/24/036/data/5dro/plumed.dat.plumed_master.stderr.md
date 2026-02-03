**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmkj6or:04893] *** Process received signal ***
[runnervmkj6or:04893] Signal: Aborted (6)
[runnervmkj6or:04893] Signal code:  (-6)
[runnervmkj6or:04893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab00c45330]
[runnervmkj6or:04893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab00c9eb2c]
[runnervmkj6or:04893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab00c4527e]
[runnervmkj6or:04893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab00c288ff]
[runnervmkj6or:04893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab010a5ff5]
[runnervmkj6or:04893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab010bb0da]
[runnervmkj6or:04893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab010a5a55]
[runnervmkj6or:04893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab010a5a6f]
[runnervmkj6or:04893] [ 8] plumed_master(+0x146dd)[0x562c46d7e6dd]
[runnervmkj6or:04893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab00c2a1ca]
[runnervmkj6or:04893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab00c2a28b]
[runnervmkj6or:04893] [11] plumed_master(+0x15365)[0x562c46d7f365]
[runnervmkj6or:04893] *** End of error message ***
</pre>
{% endraw %}
