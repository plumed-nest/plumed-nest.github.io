**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvm7jw40e0xgp:05933] *** Process received signal ***
[pkrvm7jw40e0xgp:05933] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05933] Signal code:  (-6)
[pkrvm7jw40e0xgp:05933] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6bc4445330]
[pkrvm7jw40e0xgp:05933] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6bc449eb2c]
[pkrvm7jw40e0xgp:05933] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6bc444527e]
[pkrvm7jw40e0xgp:05933] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6bc44288ff]
[pkrvm7jw40e0xgp:05933] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6bc48a5ff5]
[pkrvm7jw40e0xgp:05933] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6bc48bb0da]
[pkrvm7jw40e0xgp:05933] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6bc48a5a55]
[pkrvm7jw40e0xgp:05933] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6bc48a5a6f]
[pkrvm7jw40e0xgp:05933] [ 8] plumed(+0x146dd)[0x5595433ea6dd]
[pkrvm7jw40e0xgp:05933] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6bc442a1ca]
[pkrvm7jw40e0xgp:05933] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6bc442a28b]
[pkrvm7jw40e0xgp:05933] [11] plumed(+0x15365)[0x5595433eb365]
[pkrvm7jw40e0xgp:05933] *** End of error message ***
</pre>
{% endraw %}
