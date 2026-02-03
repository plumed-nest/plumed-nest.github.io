**Project ID:** [plumID:21.040]({{ '/' | absolute_url }}eggs/21/040/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @38 : cannot understand the following words from the input line : REF0, REF1, REF10, REF11, REF12, REF13, REF14, REF15, REF16, REF17, REF18, REF19, REF2, REF20, REF21, REF22, REF23, REF24, REF25, REF26, REF27, REF28, REF3, REF4, REF5, REF6, REF7, REF8, REF9
[runnervmkj6or:10920] *** Process received signal ***
[runnervmkj6or:10920] Signal: Aborted (6)
[runnervmkj6or:10920] Signal code:  (-6)
[runnervmkj6or:10920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f33b8e45330]
[runnervmkj6or:10920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f33b8e9eb2c]
[runnervmkj6or:10920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f33b8e4527e]
[runnervmkj6or:10920] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33b8e288ff]
[runnervmkj6or:10920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33b92a5ff5]
[runnervmkj6or:10920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33b92bb0da]
[runnervmkj6or:10920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33b92a5a55]
[runnervmkj6or:10920] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33b92a5a6f]
[runnervmkj6or:10920] [ 8] plumed_master(+0x146dd)[0x55e6159c26dd]
[runnervmkj6or:10920] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f33b8e2a1ca]
[runnervmkj6or:10920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f33b8e2a28b]
[runnervmkj6or:10920] [11] plumed_master(+0x15365)[0x55e6159c3365]
[runnervmkj6or:10920] *** End of error message ***
</pre>
{% endraw %}
