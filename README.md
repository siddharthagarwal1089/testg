## Role Variables
Variables in defaults/main.yml:<br>
  (All these variables needs to changed accordingly) <br>
      output_path: "/tmp/health_check_report.txt" <br>
      host_storing_hc_report: localhost <br>
      default_host: appmail.prod.entergy.com <br>
      default_port: 25 <br>
      default_from: "ENTER MAIL ADDRESS" <br>
      default_to: "ENTER MAIL ADDRESS" <br>
      default_subject: "ENTER SUBJECT" <br>
      default_body: "ENTER BODY" <br>
      default_attach: "{{ output_path }}" <br>
