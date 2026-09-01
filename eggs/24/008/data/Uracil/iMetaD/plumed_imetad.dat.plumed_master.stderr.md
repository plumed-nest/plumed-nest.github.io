**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmgx7h7:06047] *** Process received signal ***
[runnervmgx7h7:06047] Signal: Aborted (6)
[runnervmgx7h7:06047] Signal code:  (-6)
[runnervmgx7h7:06047] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1f25e45330]
[runnervmgx7h7:06047] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1f25e9ec0c]
[runnervmgx7h7:06047] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1f25e4527e]
[runnervmgx7h7:06047] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1f25e288ff]
[runnervmgx7h7:06047] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1f262a5ff5]
[runnervmgx7h7:06047] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1f262bb0da]
[runnervmgx7h7:06047] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1f262a5a55]
[runnervmgx7h7:06047] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1f262a5a6f]
[runnervmgx7h7:06047] [ 8] plumed_master(+0x146dd)[0x563133a166dd]
[runnervmgx7h7:06047] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1f25e2a1ca]
[runnervmgx7h7:06047] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1f25e2a28b]
[runnervmgx7h7:06047] [11] plumed_master(+0x15365)[0x563133a17365]
[runnervmgx7h7:06047] *** End of error message ***
</pre>
{% endraw %}
