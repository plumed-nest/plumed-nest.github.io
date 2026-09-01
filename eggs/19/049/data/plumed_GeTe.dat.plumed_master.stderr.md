**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmgx7h7:12365] *** Process received signal ***
[runnervmgx7h7:12365] Signal: Aborted (6)
[runnervmgx7h7:12365] Signal code:  (-6)
[runnervmgx7h7:12365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bc7e45330]
[runnervmgx7h7:12365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bc7e9ec0c]
[runnervmgx7h7:12365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bc7e4527e]
[runnervmgx7h7:12365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bc7e288ff]
[runnervmgx7h7:12365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bc82a5ff5]
[runnervmgx7h7:12365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bc82bb0da]
[runnervmgx7h7:12365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bc82a5a55]
[runnervmgx7h7:12365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bc82a5a6f]
[runnervmgx7h7:12365] [ 8] plumed_master(+0x146dd)[0x55a9c2bfc6dd]
[runnervmgx7h7:12365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bc7e2a1ca]
[runnervmgx7h7:12365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bc7e2a28b]
[runnervmgx7h7:12365] [11] plumed_master(+0x15365)[0x55a9c2bfd365]
[runnervmgx7h7:12365] *** End of error message ***
</pre>
{% endraw %}
