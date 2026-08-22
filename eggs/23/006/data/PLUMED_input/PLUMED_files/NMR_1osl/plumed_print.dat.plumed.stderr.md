**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervm76f27:07162] *** Process received signal ***
[runnervm76f27:07162] Signal: Aborted (6)
[runnervm76f27:07162] Signal code:  (-6)
[runnervm76f27:07162] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3763045330]
[runnervm76f27:07162] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f376309ec0c]
[runnervm76f27:07162] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f376304527e]
[runnervm76f27:07162] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37630288ff]
[runnervm76f27:07162] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37634a5ff5]
[runnervm76f27:07162] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37634bb0da]
[runnervm76f27:07162] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37634a5a55]
[runnervm76f27:07162] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37634a5a6f]
[runnervm76f27:07162] [ 8] plumed(+0x146dd)[0x561f229d06dd]
[runnervm76f27:07162] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f376302a1ca]
[runnervm76f27:07162] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f376302a28b]
[runnervm76f27:07162] [11] plumed(+0x15365)[0x561f229d1365]
[runnervm76f27:07162] *** End of error message ***
</pre>
{% endraw %}
