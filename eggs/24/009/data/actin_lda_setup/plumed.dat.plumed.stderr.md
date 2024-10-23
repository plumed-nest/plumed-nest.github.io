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
[fv-az585-767:03966] *** Process received signal ***
[fv-az585-767:03966] Signal: Aborted (6)
[fv-az585-767:03966] Signal code:  (-6)
[fv-az585-767:03966] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efcfb442520]
[fv-az585-767:03966] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efcfb4969fc]
[fv-az585-767:03966] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efcfb442476]
[fv-az585-767:03966] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efcfb4287f3]
[fv-az585-767:03966] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efcfb8a2b9e]
[fv-az585-767:03966] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efcfb8ae20c]
[fv-az585-767:03966] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efcfb8ae277]
[fv-az585-767:03966] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efcfb8ae52b]
[fv-az585-767:03966] [ 8] plumed(+0x14254)[0x562f4d35a254]
[fv-az585-767:03966] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efcfb429d90]
[fv-az585-767:03966] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efcfb429e40]
[fv-az585-767:03966] [11] plumed(+0x14eb5)[0x562f4d35aeb5]
[fv-az585-767:03966] *** End of error message ***
</pre>
{% endraw %}
