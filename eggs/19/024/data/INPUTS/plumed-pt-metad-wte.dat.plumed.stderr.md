**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervmw9dnm:12127] *** Process received signal ***
[runnervmw9dnm:12127] Signal: Aborted (6)
[runnervmw9dnm:12127] Signal code:  (-6)
[runnervmw9dnm:12127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f682be45330]
[runnervmw9dnm:12127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f682be9eb2c]
[runnervmw9dnm:12127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f682be4527e]
[runnervmw9dnm:12127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f682be288ff]
[runnervmw9dnm:12127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f682c2a5ff5]
[runnervmw9dnm:12127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f682c2bb0da]
[runnervmw9dnm:12127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f682c2a5a55]
[runnervmw9dnm:12127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f682c2a5a6f]
[runnervmw9dnm:12127] [ 8] plumed(+0x146dd)[0x5585da6a56dd]
[runnervmw9dnm:12127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f682be2a1ca]
[runnervmw9dnm:12127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f682be2a28b]
[runnervmw9dnm:12127] [11] plumed(+0x15365)[0x5585da6a6365]
[runnervmw9dnm:12127] *** End of error message ***
</pre>
{% endraw %}
