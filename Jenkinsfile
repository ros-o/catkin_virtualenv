#!/usr/bin/env groovy
@Library('tailor-meta@test-kal')_
tailorTestPipeline(
  // Name of job that generated this test definition.
  rosdistro_job: '/ci/rosdistro/feature%2Ftest-kal',
  // Distribution name
  rosdistro_name: 'ros1',
  // Release track to test branch against.
  release_track: 'hotdog',
  // Release label to pull test images from.
  release_label: 'hotdog',
  // OS distributions to test.
  distributions: ['jammy'],
  // Version of tailor_meta to build against
  tailor_meta: 'test-kal',
  // Master or release branch associated with this track
  source_branch: 'master',
  // Docker registry where test image is stored
  docker_registry: 'https://084758475884.dkr.ecr.us-east-1.amazonaws.com/locus-tailor'
)