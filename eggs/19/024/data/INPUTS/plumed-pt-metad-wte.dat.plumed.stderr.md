**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervm76f27:11809] *** Process received signal ***
[runnervm76f27:11809] Signal: Aborted (6)
[runnervm76f27:11809] Signal code:  (-6)
[runnervm76f27:11809] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98e3a45330]
[runnervm76f27:11809] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98e3a9ec0c]
[runnervm76f27:11809] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98e3a4527e]
[runnervm76f27:11809] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98e3a288ff]
[runnervm76f27:11809] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98e3ea5ff5]
[runnervm76f27:11809] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98e3ebb0da]
[runnervm76f27:11809] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98e3ea5a55]
[runnervm76f27:11809] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98e3ea5a6f]
[runnervm76f27:11809] [ 8] plumed(+0x146dd)[0x5635e76126dd]
[runnervm76f27:11809] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98e3a2a1ca]
[runnervm76f27:11809] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98e3a2a28b]
[runnervm76f27:11809] [11] plumed(+0x15365)[0x5635e7613365]
[runnervm76f27:11809] *** End of error message ***
</pre>
{% endraw %}
