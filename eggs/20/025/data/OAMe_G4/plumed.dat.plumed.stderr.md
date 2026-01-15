**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G4/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[runnervmi13qx:33713] *** Process received signal ***
[runnervmi13qx:33713] Signal: Aborted (6)
[runnervmi13qx:33713] Signal code:  (-6)
[runnervmi13qx:33713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5b0a45330]
[runnervmi13qx:33713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5b0a9eb2c]
[runnervmi13qx:33713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5b0a4527e]
[runnervmi13qx:33713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5b0a288ff]
[runnervmi13qx:33713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5b0ea5ff5]
[runnervmi13qx:33713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5b0ebb0da]
[runnervmi13qx:33713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5b0ea5a55]
[runnervmi13qx:33713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5b0ea5a6f]
[runnervmi13qx:33713] [ 8] plumed(+0x146dd)[0x55b049f096dd]
[runnervmi13qx:33713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5b0a2a1ca]
[runnervmi13qx:33713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5b0a2a28b]
[runnervmi13qx:33713] [11] plumed(+0x15365)[0x55b049f0a365]
[runnervmi13qx:33713] *** End of error message ***
</pre>
{% endraw %}
