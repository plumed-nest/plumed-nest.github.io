**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmkj6or:04832] *** Process received signal ***
[runnervmkj6or:04832] Signal: Aborted (6)
[runnervmkj6or:04832] Signal code:  (-6)
[runnervmkj6or:04832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a22a45330]
[runnervmkj6or:04832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a22a9eb2c]
[runnervmkj6or:04832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a22a4527e]
[runnervmkj6or:04832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a22a288ff]
[runnervmkj6or:04832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a22ea5ff5]
[runnervmkj6or:04832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a22ebb0da]
[runnervmkj6or:04832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a22ea5a55]
[runnervmkj6or:04832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a22ea5a6f]
[runnervmkj6or:04832] [ 8] plumed_master(+0x146dd)[0x55636068b6dd]
[runnervmkj6or:04832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a22a2a1ca]
[runnervmkj6or:04832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a22a2a28b]
[runnervmkj6or:04832] [11] plumed_master(+0x15365)[0x55636068c365]
[runnervmkj6or:04832] *** End of error message ***
</pre>
{% endraw %}
