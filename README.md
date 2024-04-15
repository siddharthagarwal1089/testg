## Role Variables

Variables in defaults/main.yml:
  (All these variables needs to changed accordingly)
      output_path: "/tmp/health_check_report.txt"
      host_storing_hc_report: localhost 
      default_host: appmail.prod.entergy.com
      default_port: 25
      default_from: "ENTER MAIL ADDRESS"
      default_to: "ENTER MAIL ADDRESS"
      default_subject: "ENTER SUBJECT"
      default_body: "ENTER BODY"
      default_attach: "{{ output_path }}"
