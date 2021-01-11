**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
(download [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7feb59cd84b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7feb59cd8428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7feb59cda02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7feb5a31284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7feb5a3106b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7feb5a310701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7feb5a310969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7feb59cc3830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12367] *** End of error message ***
</pre>
{% endraw %}
