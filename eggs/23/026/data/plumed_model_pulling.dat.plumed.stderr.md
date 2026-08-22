**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm76f27:07296] *** Process received signal ***
[runnervm76f27:07296] Signal: Aborted (6)
[runnervm76f27:07296] Signal code:  (-6)
[runnervm76f27:07296] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7b7645330]
[runnervm76f27:07296] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7b769ec0c]
[runnervm76f27:07296] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7b764527e]
[runnervm76f27:07296] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7b76288ff]
[runnervm76f27:07296] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7b7aa5ff5]
[runnervm76f27:07296] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7b7abb0da]
[runnervm76f27:07296] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7b7aa5a55]
[runnervm76f27:07296] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7b7aa5a6f]
[runnervm76f27:07296] [ 8] plumed(+0x146dd)[0x5653206666dd]
[runnervm76f27:07296] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7b762a1ca]
[runnervm76f27:07296] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7b762a28b]
[runnervm76f27:07296] [11] plumed(+0x15365)[0x565320667365]
[runnervm76f27:07296] *** End of error message ***
</pre>
{% endraw %}
