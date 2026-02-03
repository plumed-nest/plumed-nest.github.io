**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervmkj6or:06417] *** Process received signal ***
[runnervmkj6or:06417] Signal: Aborted (6)
[runnervmkj6or:06417] Signal code:  (-6)
[runnervmkj6or:06417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc69b045330]
[runnervmkj6or:06417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc69b09eb2c]
[runnervmkj6or:06417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc69b04527e]
[runnervmkj6or:06417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc69b0288ff]
[runnervmkj6or:06417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc69b4a5ff5]
[runnervmkj6or:06417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc69b4bb0da]
[runnervmkj6or:06417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc69b4a5a55]
[runnervmkj6or:06417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc69b4a5a6f]
[runnervmkj6or:06417] [ 8] plumed_master(+0x146dd)[0x556971fce6dd]
[runnervmkj6or:06417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc69b02a1ca]
[runnervmkj6or:06417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc69b02a28b]
[runnervmkj6or:06417] [11] plumed_master(+0x15365)[0x556971fcf365]
[runnervmkj6or:06417] *** End of error message ***
</pre>
{% endraw %}
