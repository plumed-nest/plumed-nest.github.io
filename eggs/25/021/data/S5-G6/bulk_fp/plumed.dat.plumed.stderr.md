**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G6/bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05751] *** Process received signal ***
[runnervmeorf1:05751] Signal: Aborted (6)
[runnervmeorf1:05751] Signal code:  (-6)
[runnervmeorf1:05751] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f880b245330]
[runnervmeorf1:05751] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f880b29eb2c]
[runnervmeorf1:05751] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f880b24527e]
[runnervmeorf1:05751] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f880b2288ff]
[runnervmeorf1:05751] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f880b6a5ff5]
[runnervmeorf1:05751] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f880b6bb0da]
[runnervmeorf1:05751] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f880b6a5a55]
[runnervmeorf1:05751] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f880b6a5a6f]
[runnervmeorf1:05751] [ 8] plumed(+0x146dd)[0x55d630d4f6dd]
[runnervmeorf1:05751] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f880b22a1ca]
[runnervmeorf1:05751] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f880b22a28b]
[runnervmeorf1:05751] [11] plumed(+0x15365)[0x55d630d50365]
[runnervmeorf1:05751] *** End of error message ***
</pre>
{% endraw %}
