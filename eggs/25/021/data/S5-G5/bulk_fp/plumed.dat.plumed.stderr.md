**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G5/bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05596] *** Process received signal ***
[runnervmeorf1:05596] Signal: Aborted (6)
[runnervmeorf1:05596] Signal code:  (-6)
[runnervmeorf1:05596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f259cc45330]
[runnervmeorf1:05596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f259cc9eb2c]
[runnervmeorf1:05596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f259cc4527e]
[runnervmeorf1:05596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f259cc288ff]
[runnervmeorf1:05596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f259d0a5ff5]
[runnervmeorf1:05596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f259d0bb0da]
[runnervmeorf1:05596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f259d0a5a55]
[runnervmeorf1:05596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f259d0a5a6f]
[runnervmeorf1:05596] [ 8] plumed(+0x146dd)[0x562ac1eaf6dd]
[runnervmeorf1:05596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f259cc2a1ca]
[runnervmeorf1:05596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f259cc2a28b]
[runnervmeorf1:05596] [11] plumed(+0x15365)[0x562ac1eb0365]
[runnervmeorf1:05596] *** End of error message ***
</pre>
{% endraw %}
