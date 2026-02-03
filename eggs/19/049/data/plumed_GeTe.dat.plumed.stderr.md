**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmkj6or:08586] *** Process received signal ***
[runnervmkj6or:08586] Signal: Aborted (6)
[runnervmkj6or:08586] Signal code:  (-6)
[runnervmkj6or:08586] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f097dc45330]
[runnervmkj6or:08586] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f097dc9eb2c]
[runnervmkj6or:08586] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f097dc4527e]
[runnervmkj6or:08586] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f097dc288ff]
[runnervmkj6or:08586] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f097e0a5ff5]
[runnervmkj6or:08586] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f097e0bb0da]
[runnervmkj6or:08586] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f097e0a5a55]
[runnervmkj6or:08586] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f097e0a5a6f]
[runnervmkj6or:08586] [ 8] plumed(+0x146dd)[0x55adef4ee6dd]
[runnervmkj6or:08586] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f097dc2a1ca]
[runnervmkj6or:08586] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f097dc2a28b]
[runnervmkj6or:08586] [11] plumed(+0x15365)[0x55adef4ef365]
[runnervmkj6or:08586] *** End of error message ***
</pre>
{% endraw %}
