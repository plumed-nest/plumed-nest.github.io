**Project ID:** [plumID:24.026]({{ '/' | absolute_url }}eggs/24/026/)  
Stderr for source:  CpHMD_metaD/scripts/PLUMED_GRID.dat   
Download: [zipped raw stdout](PLUMED_GRID.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](PLUMED_GRID.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervm76f27:05199] *** Process received signal ***
[runnervm76f27:05199] Signal: Aborted (6)
[runnervm76f27:05199] Signal code:  (-6)
[runnervm76f27:05199] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19fba45330]
[runnervm76f27:05199] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19fba9ec0c]
[runnervm76f27:05199] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19fba4527e]
[runnervm76f27:05199] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19fba288ff]
[runnervm76f27:05199] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19fbea5ff5]
[runnervm76f27:05199] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19fbebb0da]
[runnervm76f27:05199] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19fbea5a55]
[runnervm76f27:05199] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19fbea5a6f]
[runnervm76f27:05199] [ 8] plumed_master(+0x146dd)[0x55cc5f3a56dd]
[runnervm76f27:05199] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19fba2a1ca]
[runnervm76f27:05199] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19fba2a28b]
[runnervm76f27:05199] [11] plumed_master(+0x15365)[0x55cc5f3a6365]
[runnervm76f27:05199] *** End of error message ***
</pre>
{% endraw %}
