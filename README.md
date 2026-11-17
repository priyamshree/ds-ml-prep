# ds-ml-prep

hello, this is a ds ml pipeline. i want you to work on this
we will work onnthis,
Artifacts should be uploaded only after a successful build and local validation on the execution host.

On transfer, we will compare SHA-256 hashes. A mismatch must fail validation.

We will retain the original .pth and canonical .onnx files so that TensorRT engines can be regenerated if the target GPU or runtime changes.
