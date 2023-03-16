#!/bin/bash

if [ "$SOME_ENV" = "PRODUCTION" ] ; then
  exec npm run migration
else
  echo "Postdeploy hook disabled"
  exit 0
fi