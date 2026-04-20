**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G6/anti_bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05716] *** Process received signal ***
[runnervmeorf1:05716] Signal: Aborted (6)
[runnervmeorf1:05716] Signal code:  (-6)
[runnervmeorf1:05716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff98cc45330]
[runnervmeorf1:05716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff98cc9eb2c]
[runnervmeorf1:05716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff98cc4527e]
[runnervmeorf1:05716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff98cc288ff]
[runnervmeorf1:05716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff98d0a5ff5]
[runnervmeorf1:05716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff98d0bb0da]
[runnervmeorf1:05716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff98d0a5a55]
[runnervmeorf1:05716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff98d0a5a6f]
[runnervmeorf1:05716] [ 8] plumed_master(+0x146dd)[0x55a8a65836dd]
[runnervmeorf1:05716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff98cc2a1ca]
[runnervmeorf1:05716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff98cc2a28b]
[runnervmeorf1:05716] [11] plumed_master(+0x15365)[0x55a8a6584365]
[runnervmeorf1:05716] *** End of error message ***
</pre>
{% endraw %}
