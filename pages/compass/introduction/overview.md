import { withRouter } from 'next/router'
import WithMDX from '../../../lib/with-mdx'

import { lewi } from '../../../lib/data/team'

export const page = {
title: 'Compass Overview',
date: '4 Sep 2018',
authors: [lewi],
editUrl: 'pages/compass/introduction/overview.md',
}

export default withRouter(props => WithMDX(props, page))

Compass is an open-source implementation of an IOTA Network coordinator. It is used to ensure the Tangle it is connected to is moving in a uniform direction and to protect against various attacks a young Tangle is susceptible to. 

### Making Compass obsolete

Considerable research is underway towards a viable replacement for the Coordinator.  Releasing Compass, an open source coordinator, will further this research.  

### Repository
Jump directly to the Compass source code on [Github](https://github.com/iotaledger/compass)

### Releases
See the Github page for [Releases](https://github.com/iotaledger/compass/releases)