===RULES RE ACCEPTABLE CONTENT FOR agile PROJECT===

1) git branching model 

WE USE FEATURE-BRANCH METHOD\n
EACH TEAM MEMBER TO CREATE THEIR OWN LOCAL BRANCH
PULL FROM REMOTE MASTER REGULARLY (checks for updates)
MERGE IN YOUR CHANGES (and wait for administrator of remote MASTER repo to approve them)
THEN RE-PULL FROM MASTER AND REPEAT WITH YOUR NEXT 'FEATURE'



2) Items to include in this git repo

MUST BE AUTOMATED ARTEFACTS ONLY:-

 DOCKER CONTAINER FILES (Dockerfile)

 PUPPET MANIFESTS (module.pp)

 SCRIPTS (RULES: must be annotated, modular, use runtime/envt variable files (no hardcoding of vars) 
  -bash
  -ruby(is ruby installed by default?)  

 RPMS 

 JENKINS WORKSPACE JOBS (simply copy workspace directory from under $JENKINS_HOME)?

**absolutely no WORD docs!**
