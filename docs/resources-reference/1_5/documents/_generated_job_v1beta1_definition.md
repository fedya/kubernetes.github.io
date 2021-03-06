## Job v1beta1

Group        | Version     | Kind
------------ | ---------- | -----------
Core | v1beta1 | Job

<aside class="notice">Other api versions of this object exist: <a href="#job-v1">v1</a> <a href="#job-v2alpha1">v2alpha1</a> </aside>

Job represents the configuration of a single job. DEPRECATED: extensions/v1beta1.Job is deprecated, use batch/v1.Job instead.

<aside class="notice">
Appears In  <a href="#joblist-v1beta1">JobList</a> </aside>

Field        | Description
------------ | -----------
metadata <br /> *[ObjectMeta](#objectmeta-v1)*  | Standard object's metadata. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#metadata
spec <br /> *[JobSpec](#jobspec-v1beta1)*  | Spec is a structure defining the expected behavior of a job. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#spec-and-status
status <br /> *[JobStatus](#jobstatus-v1beta1)*  | Status is a structure describing current status of a job. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#spec-and-status

