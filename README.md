# Render engine

A public render farm for a private video pipeline. It holds no content and no publishing credentials.
Each scheduled job checks out the private repo with a read/write token, takes the next queued lesson,
renders it, and returns the result to the private repo. Publishing happens only in the private repo.

Source of truth: `engine-public/` in the private repo. Edit it there, then copy it here.
