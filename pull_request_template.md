# Issue
Link this PR to an issue, if possible. <br> 
Issue number: 

# Changes
### What has changed - and why?
1.

# Checklist
Please fill out the below checklist. <br>
When filling out the checklist you confirm that your application is following the checked guidelines.

### Recommended
<!-- ignore-task-list-start -->

- [ ] All configuration through environment variables
- [ ] Using correlation id in HTTP header ‘X-Request-Id’
- [ ] Logging correlation id to field ```request_id```
- [ ] A health URL are usede for readinessProbe ore livenessProbe
- [ ] A Prometheus metric URL are configured
- [ ] The application is stateless. States are stored in a datastore
- [ ] Backup interval and retention is handlet by the application supplier, either through the platform or in the application.
- [ ] If an application requires login, RSJ’s existing login infrastructure are used

<!-- ignore-task-list-end -->

### Required
- [ ] Application log is sent to stdout. Logs must not contain sensitive information. The format should be JSON.
- [ ] Logs containing sensitive information are logged to the Audit API
- [ ] Resource limits and request for CPU and memory are set in the configuration