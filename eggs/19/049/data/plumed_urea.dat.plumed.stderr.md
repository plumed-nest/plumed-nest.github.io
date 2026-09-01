**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmgx7h7:12440] *** Process received signal ***
[runnervmgx7h7:12440] Signal: Aborted (6)
[runnervmgx7h7:12440] Signal code:  (-6)
[runnervmgx7h7:12440] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f140a845330]
[runnervmgx7h7:12440] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f140a89ec0c]
[runnervmgx7h7:12440] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f140a84527e]
[runnervmgx7h7:12440] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f140a8288ff]
[runnervmgx7h7:12440] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f140aca5ff5]
[runnervmgx7h7:12440] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f140acbb0da]
[runnervmgx7h7:12440] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f140aca5a55]
[runnervmgx7h7:12440] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f140aca5a6f]
[runnervmgx7h7:12440] [ 8] plumed(+0x146dd)[0x557570f566dd]
[runnervmgx7h7:12440] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f140a82a1ca]
[runnervmgx7h7:12440] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f140a82a28b]
[runnervmgx7h7:12440] [11] plumed(+0x15365)[0x557570f57365]
[runnervmgx7h7:12440] *** End of error message ***
</pre>
{% endraw %}
