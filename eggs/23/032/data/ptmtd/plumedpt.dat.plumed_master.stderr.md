**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm76f27:04789] *** Process received signal ***
[runnervm76f27:04789] Signal: Aborted (6)
[runnervm76f27:04789] Signal code:  (-6)
[runnervm76f27:04789] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d46445330]
[runnervm76f27:04789] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d4649ec0c]
[runnervm76f27:04789] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d4644527e]
[runnervm76f27:04789] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d464288ff]
[runnervm76f27:04789] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d468a5ff5]
[runnervm76f27:04789] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d468bb0da]
[runnervm76f27:04789] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d468a5a55]
[runnervm76f27:04789] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d468a5a6f]
[runnervm76f27:04789] [ 8] plumed_master(+0x146dd)[0x560e76adc6dd]
[runnervm76f27:04789] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d4642a1ca]
[runnervm76f27:04789] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d4642a28b]
[runnervm76f27:04789] [11] plumed_master(+0x15365)[0x560e76add365]
[runnervm76f27:04789] *** End of error message ***
</pre>
{% endraw %}
