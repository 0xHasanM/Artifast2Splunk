# Artifast2Splunk
Artifast2Splunk is a collection of Splunk configuration files for ingesting, and parsing json output from artifast in Splunk.

Quick start

- Clone the repo and copy props.conf, and macros.conf into $SPLUNK_HOME/etc/.
- Restart Splunk.
- Upload json output from artifast to splunk and set sourcetype to artifast.
- Use "artifast_evtx_parse" with event logs output for fields parsing.
