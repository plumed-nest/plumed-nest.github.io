**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[runnervmmklqx:08644] *** Process received signal ***
[runnervmmklqx:08644] Signal: Aborted (6)
[runnervmmklqx:08644] Signal code:  (-6)
[runnervmmklqx:08644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7febd1c45330]
[runnervmmklqx:08644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7febd1c9eb2c]
[runnervmmklqx:08644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7febd1c4527e]
[runnervmmklqx:08644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7febd1c288ff]
[runnervmmklqx:08644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7febd20a5ff5]
[runnervmmklqx:08644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7febd20bb0da]
[runnervmmklqx:08644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7febd20a5a55]
[runnervmmklqx:08644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7febd20a5a6f]
[runnervmmklqx:08644] [ 8] plumed_master(+0x146dd)[0x557a324816dd]
[runnervmmklqx:08644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7febd1c2a1ca]
[runnervmmklqx:08644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7febd1c2a28b]
[runnervmmklqx:08644] [11] plumed_master(+0x15365)[0x557a32482365]
[runnervmmklqx:08644] *** End of error message ***
</pre>
{% endraw %}
