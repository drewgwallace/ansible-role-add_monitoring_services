# Ansible Role



## Purpose
  Execute this role against a supported server, it will add the InfluxData repository and key, then install Telegraf with apt-get (Debian based systems).
  
----

## Execution
<pre>
    - hosts: all
      tasks:
        - include_role:
            name: drewgwallace.ansible-role-add_monitoring_services
</pre>

----

## Notes

