<script>
	import Race from '../../components/Race.svelte';

	let response = [
		{
			id: 43593,
			type: 'ind',
			competitor: {
				number: 213,
				identifier: 'F213',
				skater: {
					id: 1082,
					firstName: 'Dan',
					lastName: 'Guo',
					country: 'CHN',
					gender: 'F',
					dateOfBirth: '1990-12-06',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCHN20612199001',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/1082.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/1082/personal-best/',
					created: '2017-10-28T15:30:30.724301Z',
					modified: '2022-01-09T15:28:51.175970Z'
				}
			},
			startNumber: 1,
			startLane: 'I',
			armband: 'white',
			rank: 21,
			status: 0,
			time: '4:37.400',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.931921Z',
			modified: '2018-01-18T14:35:48.838658Z',
			laps: [
				{
					number: 1,
					time: '21.50',
					passageTime: '21.500'
				},
				{
					number: 2,
					time: '34.20',
					passageTime: '55.730'
				},
				{
					number: 3,
					time: '35.70',
					passageTime: '1:31.450'
				},
				{
					number: 4,
					time: '36.60',
					passageTime: '2:08.140'
				},
				{
					number: 5,
					time: '37.00',
					passageTime: '2:45.220'
				},
				{
					number: 6,
					time: '37.10',
					passageTime: '3:22.320'
				},
				{
					number: 7,
					time: '37.50',
					passageTime: '3:59.840'
				},
				{
					number: 8,
					time: '37.50',
					passageTime: '4:37.400'
				}
			]
		},
		{
			id: 43594,
			type: 'ind',
			competitor: {
				number: 216,
				identifier: 'F216',
				skater: {
					id: 1057,
					firstName: 'Dan',
					lastName: 'Li',
					country: 'CHN',
					gender: 'F',
					dateOfBirth: '1994-05-06',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCHN10605199401',
					photo: 'https://media.isuresults.eu/2018/12/14/1057.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/1057/personal-best/',
					created: '2017-10-28T15:03:30.042005Z',
					modified: '2018-12-14T15:42:15.183889Z'
				}
			},
			startNumber: 2,
			startLane: 'I',
			armband: 'white',
			rank: 18,
			status: 0,
			time: '4:27.200',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.935121Z',
			modified: '2018-01-18T14:35:48.807470Z',
			laps: [
				{
					number: 1,
					time: '21.10',
					passageTime: '21.170'
				},
				{
					number: 2,
					time: '32.10',
					passageTime: '53.360'
				},
				{
					number: 3,
					time: '33.20',
					passageTime: '1:26.630'
				},
				{
					number: 4,
					time: '34.40',
					passageTime: '2:01.080'
				},
				{
					number: 5,
					time: '35.40',
					passageTime: '2:36.550'
				},
				{
					number: 6,
					time: '36.40',
					passageTime: '3:13.030'
				},
				{
					number: 7,
					time: '36.90',
					passageTime: '3:49.970'
				},
				{
					number: 8,
					time: '37.20',
					passageTime: '4:27.200'
				}
			]
		},
		{
			id: 43595,
			type: 'ind',
			competitor: {
				number: 231,
				identifier: 'F231',
				skater: {
					id: 270,
					firstName: 'Elena Møller',
					lastName: 'Rigas',
					country: 'DEN',
					gender: 'F',
					dateOfBirth: '1996-01-29',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSDEN22901199601',
					photo: 'https://media.isuresults.eu/2018/12/14/270.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/270/personal-best/',
					created: '2017-10-28T13:29:51.077583Z',
					modified: '2018-12-14T15:42:10.053423Z'
				}
			},
			startNumber: 2,
			startLane: 'O',
			armband: 'red',
			rank: 19,
			status: 0,
			time: '4:28.000',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.937291Z',
			modified: '2018-01-18T14:35:48.816658Z',
			laps: [
				{
					number: 1,
					time: '20.60',
					passageTime: '20.700'
				},
				{
					number: 2,
					time: '32.70',
					passageTime: '53.400'
				},
				{
					number: 3,
					time: '34.50',
					passageTime: '1:27.980'
				},
				{
					number: 4,
					time: '34.80',
					passageTime: '2:02.840'
				},
				{
					number: 5,
					time: '35.80',
					passageTime: '2:38.730'
				},
				{
					number: 6,
					time: '35.90',
					passageTime: '3:14.690'
				},
				{
					number: 7,
					time: '36.60',
					passageTime: '3:51.340'
				},
				{
					number: 8,
					time: '36.60',
					passageTime: '4:28.000'
				}
			]
		},
		{
			id: 43596,
			type: 'ind',
			competitor: {
				number: 275,
				identifier: 'F275',
				skater: {
					id: 481,
					firstName: 'Katarzyna',
					lastName: 'Bachleda-Curus',
					country: 'POL',
					gender: 'F',
					dateOfBirth: '1980-01-01',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSPOL20101198001',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/481.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/481/personal-best/',
					created: '2017-10-28T13:30:38.982197Z',
					modified: '2018-10-27T11:54:56.206944Z'
				}
			},
			startNumber: 3,
			startLane: 'I',
			armband: 'white',
			rank: 9,
			status: 0,
			time: '4:17.710',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.939696Z',
			modified: '2018-01-18T14:35:48.723229Z',
			laps: [
				{
					number: 1,
					time: '20.70',
					passageTime: '20.760'
				},
				{
					number: 2,
					time: '31.90',
					passageTime: '52.760'
				},
				{
					number: 3,
					time: '32.10',
					passageTime: '1:24.880'
				},
				{
					number: 4,
					time: '33.00',
					passageTime: '1:57.910'
				},
				{
					number: 5,
					time: '33.70',
					passageTime: '2:31.650'
				},
				{
					number: 6,
					time: '34.50',
					passageTime: '3:06.180'
				},
				{
					number: 7,
					time: '35.30',
					passageTime: '3:41.510'
				},
				{
					number: 8,
					time: '36.10',
					passageTime: '4:17.710'
				}
			]
		},
		{
			id: 43597,
			type: 'ind',
			competitor: {
				number: 292,
				identifier: 'F292',
				skater: {
					id: 382,
					firstName: 'Mia',
					lastName: 'Kilburg',
					country: 'USA',
					gender: 'F',
					dateOfBirth: '1989-10-27',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSUSA22710198901',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/382.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/382/personal-best/',
					created: '2017-10-28T13:30:16.720389Z',
					modified: '2022-11-10T15:27:23.298408Z'
				}
			},
			startNumber: 3,
			startLane: 'O',
			armband: 'red',
			rank: 5,
			status: 0,
			time: '4:12.780',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.943223Z',
			modified: '2018-01-18T14:35:48.683958Z',
			laps: [
				{
					number: 1,
					time: '20.80',
					passageTime: '20.820'
				},
				{
					number: 2,
					time: '31.90',
					passageTime: '52.770'
				},
				{
					number: 3,
					time: '32.30',
					passageTime: '1:25.150'
				},
				{
					number: 4,
					time: '32.20',
					passageTime: '1:57.450'
				},
				{
					number: 5,
					time: '33.10',
					passageTime: '2:30.600'
				},
				{
					number: 6,
					time: '33.20',
					passageTime: '3:03.800'
				},
				{
					number: 7,
					time: '33.80',
					passageTime: '3:37.610'
				},
				{
					number: 8,
					time: '35.10',
					passageTime: '4:12.780'
				}
			]
		},
		{
			id: 43598,
			type: 'ind',
			competitor: {
				number: 257,
				identifier: 'F257',
				skater: {
					id: 23,
					firstName: 'Ji-Woo',
					lastName: 'Park',
					country: 'KOR',
					gender: 'F',
					dateOfBirth: '1998-10-27',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSKOR22710199801',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/23.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/23/personal-best/',
					created: '2017-10-28T13:28:55.107287Z',
					modified: '2022-11-10T15:24:20.113291Z'
				}
			},
			startNumber: 4,
			startLane: 'I',
			armband: 'white',
			rank: 20,
			status: 0,
			time: '4:28.790',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.945341Z',
			modified: '2018-01-18T14:35:48.825856Z',
			laps: [
				{
					number: 1,
					time: '20.70',
					passageTime: '20.750'
				},
				{
					number: 2,
					time: '33.30',
					passageTime: '54.060'
				},
				{
					number: 3,
					time: '34.70',
					passageTime: '1:28.790'
				},
				{
					number: 4,
					time: '35.70',
					passageTime: '2:04.510'
				},
				{
					number: 5,
					time: '35.80',
					passageTime: '2:40.340'
				},
				{
					number: 6,
					time: '35.90',
					passageTime: '3:16.320'
				},
				{
					number: 7,
					time: '36.00',
					passageTime: '3:52.320'
				},
				{
					number: 8,
					time: '36.40',
					passageTime: '4:28.790'
				}
			]
		},
		{
			id: 43599,
			type: 'ind',
			competitor: {
				number: 230,
				identifier: 'F230',
				skater: {
					id: 407,
					firstName: 'Nikola',
					lastName: 'Zdráhalova',
					country: 'CZE',
					gender: 'F',
					dateOfBirth: '1996-04-01',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCZE20104199601',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/407.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/407/personal-best/',
					created: '2017-10-28T13:30:22.348615Z',
					modified: '2022-01-09T15:25:58.684378Z'
				}
			},
			startNumber: 4,
			startLane: 'O',
			armband: 'red',
			rank: 16,
			status: 0,
			time: '4:24.080',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.947491Z',
			modified: '2018-01-18T14:35:48.789019Z',
			laps: [
				{
					number: 1,
					time: '19.80',
					passageTime: '19.870'
				},
				{
					number: 2,
					time: '31.70',
					passageTime: '51.660'
				},
				{
					number: 3,
					time: '33.20',
					passageTime: '1:24.900'
				},
				{
					number: 4,
					time: '34.70',
					passageTime: '1:59.610'
				},
				{
					number: 5,
					time: '35.40',
					passageTime: '2:35.020'
				},
				{
					number: 6,
					time: '35.90',
					passageTime: '3:11.000'
				},
				{
					number: 7,
					time: '36.40',
					passageTime: '3:47.420'
				},
				{
					number: 8,
					time: '36.60',
					passageTime: '4:24.080'
				}
			]
		},
		{
			id: 43600,
			type: 'ind',
			competitor: {
				number: 219,
				identifier: 'F219',
				skater: {
					id: 200,
					firstName: 'Jing',
					lastName: 'Liu',
					country: 'CHN',
					gender: 'F',
					dateOfBirth: '1988-05-30',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCHN23005198801',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/200.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/200/personal-best/',
					created: '2017-10-28T13:29:35.483005Z',
					modified: '2018-10-27T11:57:16.368935Z'
				}
			},
			startNumber: 5,
			startLane: 'I',
			armband: 'white',
			rank: 14,
			status: 0,
			time: '4:21.470',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.949636Z',
			modified: '2018-01-18T14:35:48.770362Z',
			laps: [
				{
					number: 1,
					time: '20.70',
					passageTime: '20.750'
				},
				{
					number: 2,
					time: '32.40',
					passageTime: '53.240'
				},
				{
					number: 3,
					time: '32.70',
					passageTime: '1:26.010'
				},
				{
					number: 4,
					time: '33.70',
					passageTime: '1:59.780'
				},
				{
					number: 5,
					time: '34.10',
					passageTime: '2:33.950'
				},
				{
					number: 6,
					time: '35.40',
					passageTime: '3:09.360'
				},
				{
					number: 7,
					time: '35.80',
					passageTime: '3:45.170'
				},
				{
					number: 8,
					time: '36.20',
					passageTime: '4:21.470'
				}
			]
		},
		{
			id: 43601,
			type: 'ind',
			competitor: {
				number: 279,
				identifier: 'F279',
				skater: {
					id: 816,
					firstName: 'Luiza',
					lastName: 'Zlotkowska',
					country: 'POL',
					gender: 'F',
					dateOfBirth: '1986-05-25',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSPOL22505198601',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/816.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/816/personal-best/',
					created: '2017-10-28T13:31:57.209309Z',
					modified: '2018-10-27T11:58:32.305565Z'
				}
			},
			startNumber: 5,
			startLane: 'O',
			armband: 'red',
			rank: 11,
			status: 0,
			time: '4:18.170',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.951954Z',
			modified: '2018-01-18T14:35:48.741766Z',
			laps: [
				{
					number: 1,
					time: '20.60',
					passageTime: '20.690'
				},
				{
					number: 2,
					time: '32.50',
					passageTime: '53.250'
				},
				{
					number: 3,
					time: '32.90',
					passageTime: '1:26.150'
				},
				{
					number: 4,
					time: '32.80',
					passageTime: '1:59.000'
				},
				{
					number: 5,
					time: '33.60',
					passageTime: '2:32.630'
				},
				{
					number: 6,
					time: '34.50',
					passageTime: '3:07.180'
				},
				{
					number: 7,
					time: '35.40',
					passageTime: '3:42.590'
				},
				{
					number: 8,
					time: '35.50',
					passageTime: '4:18.170'
				}
			]
		},
		{
			id: 43602,
			type: 'ind',
			competitor: {
				number: 252,
				identifier: 'F252',
				skater: {
					id: 372,
					firstName: 'Bo-Reum',
					lastName: 'Kim',
					country: 'KOR',
					gender: 'F',
					dateOfBirth: '1993-02-06',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSKOR20602199301',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/372.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/372/personal-best/',
					created: '2017-10-28T13:30:14.470681Z',
					modified: '2022-01-09T15:26:28.699841Z'
				}
			},
			startNumber: 6,
			startLane: 'I',
			armband: 'white',
			rank: 3,
			status: 0,
			time: '4:12.210',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.953945Z',
			modified: '2018-01-18T14:35:48.664433Z',
			laps: [
				{
					number: 1,
					time: '20.80',
					passageTime: '20.870'
				},
				{
					number: 2,
					time: '32.30',
					passageTime: '53.250'
				},
				{
					number: 3,
					time: '32.80',
					passageTime: '1:26.070'
				},
				{
					number: 4,
					time: '33.00',
					passageTime: '1:59.130'
				},
				{
					number: 5,
					time: '33.30',
					passageTime: '2:32.440'
				},
				{
					number: 6,
					time: '33.20',
					passageTime: '3:05.660'
				},
				{
					number: 7,
					time: '33.40',
					passageTime: '3:39.080'
				},
				{
					number: 8,
					time: '33.10',
					passageTime: '4:12.210'
				}
			]
		},
		{
			id: 43603,
			type: 'ind',
			competitor: {
				number: 215,
				identifier: 'F215',
				skater: {
					id: 717,
					firstName: 'Jiachen',
					lastName: 'Hao',
					country: 'CHN',
					gender: 'F',
					dateOfBirth: '1992-08-18',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCHN21808199201',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/717.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/717/personal-best/',
					created: '2017-10-28T13:31:33.751757Z',
					modified: '2018-10-27T11:56:45.206532Z'
				}
			},
			startNumber: 6,
			startLane: 'O',
			armband: 'red',
			rank: 12,
			status: 0,
			time: '4:20.210',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.955943Z',
			modified: '2018-01-18T14:35:48.751455Z',
			laps: [
				{
					number: 1,
					time: '20.30',
					passageTime: '20.300'
				},
				{
					number: 2,
					time: '32.20',
					passageTime: '52.510'
				},
				{
					number: 3,
					time: '33.20',
					passageTime: '1:25.740'
				},
				{
					number: 4,
					time: '33.90',
					passageTime: '1:59.730'
				},
				{
					number: 5,
					time: '34.90',
					passageTime: '2:34.640'
				},
				{
					number: 6,
					time: '34.70',
					passageTime: '3:09.400'
				},
				{
					number: 7,
					time: '35.10',
					passageTime: '3:44.590'
				},
				{
					number: 8,
					time: '35.60',
					passageTime: '4:20.210'
				}
			]
		},
		{
			id: 43604,
			type: 'ind',
			competitor: {
				number: 202,
				identifier: 'F202',
				skater: {
					id: 179,
					firstName: 'Jelena',
					lastName: 'Peeters',
					country: 'BEL',
					gender: 'F',
					dateOfBirth: '1985-12-19',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSBEL21612198501',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/179.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/179/personal-best/',
					created: '2017-10-28T13:29:30.834067Z',
					modified: '2018-10-27T11:58:31.683522Z'
				}
			},
			startNumber: 7,
			startLane: 'I',
			armband: 'white',
			rank: 7,
			status: 0,
			time: '4:16.220',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.957923Z',
			modified: '2018-01-18T14:35:48.702841Z',
			laps: [
				{
					number: 1,
					time: '20.60',
					passageTime: '20.640'
				},
				{
					number: 2,
					time: '32.00',
					passageTime: '52.730'
				},
				{
					number: 3,
					time: '32.60',
					passageTime: '1:25.360'
				},
				{
					number: 4,
					time: '33.20',
					passageTime: '1:58.580'
				},
				{
					number: 5,
					time: '33.50',
					passageTime: '2:32.110'
				},
				{
					number: 6,
					time: '34.00',
					passageTime: '3:06.200'
				},
				{
					number: 7,
					time: '34.60',
					passageTime: '3:40.860'
				},
				{
					number: 8,
					time: '35.30',
					passageTime: '4:16.220'
				}
			]
		},
		{
			id: 43605,
			type: 'ind',
			competitor: {
				number: 277,
				identifier: 'F277',
				skater: {
					id: 1055,
					firstName: 'Magdalena',
					lastName: 'Czyszczon',
					country: 'POL',
					gender: 'F',
					dateOfBirth: '1995-03-04',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSPOL20403199501',
					photo: 'https://media.isuresults.eu/skater/2022/11/19/1055.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/1055/personal-best/',
					created: '2017-10-28T14:46:01.354105Z',
					modified: '2022-11-19T13:31:10.667796Z'
				}
			},
			startNumber: 7,
			startLane: 'O',
			armband: 'red',
			rank: 13,
			status: 0,
			time: '4:20.960',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.959879Z',
			modified: '2018-01-18T14:35:48.760769Z',
			laps: [
				{
					number: 1,
					time: '21.30',
					passageTime: '21.350'
				},
				{
					number: 2,
					time: '31.80',
					passageTime: '53.180'
				},
				{
					number: 3,
					time: '33.10',
					passageTime: '1:26.340'
				},
				{
					number: 4,
					time: '33.80',
					passageTime: '2:00.190'
				},
				{
					number: 5,
					time: '34.20',
					passageTime: '2:34.420'
				},
				{
					number: 6,
					time: '35.00',
					passageTime: '3:09.420'
				},
				{
					number: 7,
					time: '35.70',
					passageTime: '3:45.130'
				},
				{
					number: 8,
					time: '35.80',
					passageTime: '4:20.960'
				}
			]
		},
		{
			id: 43606,
			type: 'ind',
			competitor: {
				number: 204,
				identifier: 'F204',
				skater: {
					id: 729,
					firstName: 'Marina',
					lastName: 'Zueva',
					country: 'BLR',
					gender: 'F',
					dateOfBirth: '1992-03-20',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSBLR22003199201',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/729.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/729/personal-best/',
					created: '2017-10-28T13:31:36.588863Z',
					modified: '2022-01-09T15:28:43.487308Z'
				}
			},
			startNumber: 8,
			startLane: 'I',
			armband: 'white',
			rank: 4,
			status: 0,
			time: '4:12.610',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.961987Z',
			modified: '2018-01-18T14:35:48.674563Z',
			laps: [
				{
					number: 1,
					time: '20.20',
					passageTime: '20.280'
				},
				{
					number: 2,
					time: '31.80',
					passageTime: '52.100'
				},
				{
					number: 3,
					time: '32.00',
					passageTime: '1:24.170'
				},
				{
					number: 4,
					time: '32.50',
					passageTime: '1:56.730'
				},
				{
					number: 5,
					time: '32.70',
					passageTime: '2:29.500'
				},
				{
					number: 6,
					time: '33.70',
					passageTime: '3:03.280'
				},
				{
					number: 7,
					time: '34.00',
					passageTime: '3:37.350'
				},
				{
					number: 8,
					time: '35.20',
					passageTime: '4:12.610'
				}
			]
		},
		{
			id: 43607,
			type: 'ind',
			competitor: {
				number: 239,
				identifier: 'F239',
				skater: {
					id: 627,
					firstName: 'Francesca',
					lastName: 'Lollobrigida',
					country: 'ITA',
					gender: 'F',
					dateOfBirth: '1991-02-07',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSITA22002199101',
					photo: 'https://media.isuresults.eu/skater/2022/01/09/627.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/627/personal-best/',
					created: '2017-10-28T13:31:12.370440Z',
					modified: '2022-01-09T15:31:46.146971Z'
				}
			},
			startNumber: 8,
			startLane: 'O',
			armband: 'red',
			rank: 2,
			status: 0,
			time: '4:11.740',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.964307Z',
			modified: '2018-01-18T14:35:48.654624Z',
			laps: [
				{
					number: 1,
					time: '20.60',
					passageTime: '20.680'
				},
				{
					number: 2,
					time: '31.60',
					passageTime: '52.280'
				},
				{
					number: 3,
					time: '32.30',
					passageTime: '1:24.640'
				},
				{
					number: 4,
					time: '32.50',
					passageTime: '1:57.220'
				},
				{
					number: 5,
					time: '33.20',
					passageTime: '2:30.440'
				},
				{
					number: 6,
					time: '33.40',
					passageTime: '3:03.890'
				},
				{
					number: 7,
					time: '33.90',
					passageTime: '3:37.840'
				},
				{
					number: 8,
					time: '33.80',
					passageTime: '4:11.740'
				}
			]
		},
		{
			id: 43608,
			type: 'ind',
			competitor: {
				number: 246,
				identifier: 'F246',
				skater: {
					id: 802,
					firstName: 'Maki',
					lastName: 'Tabata',
					country: 'JPN',
					gender: 'F',
					dateOfBirth: '1974-11-09',
					dateOfDeath: null,
					isActive: false,
					iocCode: 'SSJPN20911197401',
					photo: null,
					personalBestUrl: 'https://api.isuresults.eu/skaters/802/personal-best/',
					created: '2017-10-28T13:31:54.068391Z',
					modified: '2018-09-10T07:34:48.882970Z'
				}
			},
			startNumber: 9,
			startLane: 'I',
			armband: 'white',
			rank: 8,
			status: 0,
			time: '4:17.590',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.966312Z',
			modified: '2018-01-18T14:35:48.712257Z',
			laps: [
				{
					number: 1,
					time: '20.30',
					passageTime: '20.370'
				},
				{
					number: 2,
					time: '31.60',
					passageTime: '52.040'
				},
				{
					number: 3,
					time: '32.70',
					passageTime: '1:24.790'
				},
				{
					number: 4,
					time: '33.40',
					passageTime: '1:58.240'
				},
				{
					number: 5,
					time: '33.80',
					passageTime: '2:32.050'
				},
				{
					number: 6,
					time: '34.20',
					passageTime: '3:06.260'
				},
				{
					number: 7,
					time: '35.10',
					passageTime: '3:41.450'
				},
				{
					number: 8,
					time: '36.10',
					passageTime: '4:17.590'
				}
			]
		},
		{
			id: 43609,
			type: 'ind',
			competitor: {
				number: 245,
				identifier: 'F245',
				skater: {
					id: 1087,
					firstName: 'Ayano',
					lastName: 'Sato',
					country: 'JPN',
					gender: 'F',
					dateOfBirth: '1996-12-10',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSJPN21012199601',
					photo: 'https://media.isuresults.eu/skater/2022/11/19/1087.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/1087/personal-best/',
					created: '2017-10-28T15:30:52.488655Z',
					modified: '2022-11-19T13:31:02.412875Z'
				}
			},
			startNumber: 9,
			startLane: 'O',
			armband: 'red',
			rank: 6,
			status: 0,
			time: '4:15.900',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.968613Z',
			modified: '2018-01-18T14:35:48.693312Z',
			laps: [
				{
					number: 1,
					time: '20.20',
					passageTime: '20.250'
				},
				{
					number: 2,
					time: '32.00',
					passageTime: '52.300'
				},
				{
					number: 3,
					time: '32.60',
					passageTime: '1:24.930'
				},
				{
					number: 4,
					time: '33.10',
					passageTime: '1:58.040'
				},
				{
					number: 5,
					time: '34.30',
					passageTime: '2:32.380'
				},
				{
					number: 6,
					time: '34.50',
					passageTime: '3:06.910'
				},
				{
					number: 7,
					time: '34.90',
					passageTime: '3:41.840'
				},
				{
					number: 8,
					time: '34.00',
					passageTime: '4:15.900'
				}
			]
		},
		{
			id: 43610,
			type: 'ind',
			competitor: {
				number: 211,
				identifier: 'F211',
				skater: {
					id: 236,
					firstName: 'Brianne',
					lastName: 'Tutt',
					country: 'CAN',
					gender: 'F',
					dateOfBirth: '1992-06-09',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCAN20906199201',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/236.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/236/personal-best/',
					created: '2017-10-28T13:29:43.417221Z',
					modified: '2018-10-27T11:56:53.142037Z'
				}
			},
			startNumber: 10,
			startLane: 'I',
			armband: 'white',
			rank: 10,
			status: 0,
			time: '4:18.010',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.970595Z',
			modified: '2018-01-18T14:35:48.732447Z',
			laps: [
				{
					number: 1,
					time: '20.80',
					passageTime: '20.800'
				},
				{
					number: 2,
					time: '33.80',
					passageTime: '54.650'
				},
				{
					number: 3,
					time: '33.70',
					passageTime: '1:28.440'
				},
				{
					number: 4,
					time: '33.60',
					passageTime: '2:02.070'
				},
				{
					number: 5,
					time: '33.40',
					passageTime: '2:35.540'
				},
				{
					number: 6,
					time: '33.50',
					passageTime: '3:09.130'
				},
				{
					number: 7,
					time: '33.90',
					passageTime: '3:43.110'
				},
				{
					number: 8,
					time: '34.80',
					passageTime: '4:18.010'
				}
			]
		},
		{
			id: 43611,
			type: 'ind',
			competitor: {
				number: 214,
				identifier: 'F214',
				skater: {
					id: 1083,
					firstName: 'Mei',
					lastName: 'Han',
					country: 'CHN',
					gender: 'F',
					dateOfBirth: '1998-01-27',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSCHN22701199801',
					photo: 'https://media.isuresults.eu/skater/2022/11/19/1083.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/1083/personal-best/',
					created: '2017-10-28T15:30:31.845394Z',
					modified: '2022-11-19T13:31:09.028854Z'
				}
			},
			startNumber: 10,
			startLane: 'O',
			armband: 'red',
			rank: 17,
			status: 0,
			time: '4:25.040',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.972541Z',
			modified: '2018-01-18T14:35:48.798283Z',
			laps: [
				{
					number: 1,
					time: '20.70',
					passageTime: '20.760'
				},
				{
					number: 2,
					time: '32.40',
					passageTime: '53.190'
				},
				{
					number: 3,
					time: '33.50',
					passageTime: '1:26.780'
				},
				{
					number: 4,
					time: '34.30',
					passageTime: '2:01.130'
				},
				{
					number: 5,
					time: '34.80',
					passageTime: '2:35.990'
				},
				{
					number: 6,
					time: '35.70',
					passageTime: '3:11.700'
				},
				{
					number: 7,
					time: '36.40',
					passageTime: '3:48.150'
				},
				{
					number: 8,
					time: '36.80',
					passageTime: '4:25.040'
				}
			]
		},
		{
			id: 43612,
			type: 'ind',
			competitor: {
				number: 278,
				identifier: 'F278',
				skater: {
					id: 253,
					firstName: 'Katarzyna',
					lastName: 'Wozniak',
					country: 'POL',
					gender: 'F',
					dateOfBirth: '1989-10-05',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSPOL20510198901',
					photo: 'https://media.isuresults.eu/skater/2018/10/27/253.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/253/personal-best/',
					created: '2017-10-28T13:29:47.219321Z',
					modified: '2018-10-27T11:59:02.092426Z'
				}
			},
			startNumber: 11,
			startLane: 'I',
			armband: 'white',
			rank: 15,
			status: 0,
			time: '4:22.560',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.974957Z',
			modified: '2018-01-18T14:35:48.779585Z',
			laps: [
				{
					number: 1,
					time: '20.60',
					passageTime: '20.620'
				},
				{
					number: 2,
					time: '32.20',
					passageTime: '52.860'
				},
				{
					number: 3,
					time: '32.80',
					passageTime: '1:25.670'
				},
				{
					number: 4,
					time: '33.50',
					passageTime: '1:59.190'
				},
				{
					number: 5,
					time: '34.20',
					passageTime: '2:33.430'
				},
				{
					number: 6,
					time: '35.20',
					passageTime: '3:08.670'
				},
				{
					number: 7,
					time: '36.20',
					passageTime: '3:44.880'
				},
				{
					number: 8,
					time: '37.68',
					passageTime: '4:22.560'
				}
			]
		},
		{
			id: 43613,
			type: 'ind',
			competitor: {
				number: 236,
				identifier: 'F236',
				skater: {
					id: 314,
					firstName: 'Claudia',
					lastName: 'Pechstein',
					country: 'GER',
					gender: 'F',
					dateOfBirth: '1972-02-22',
					dateOfDeath: null,
					isActive: true,
					iocCode: 'SSGER22202197201',
					photo: 'https://media.isuresults.eu/skater/2022/11/19/314.png',
					personalBestUrl: 'https://api.isuresults.eu/skaters/314/personal-best/',
					created: '2017-10-28T13:30:01.260448Z',
					modified: '2022-11-19T13:30:59.920662Z'
				}
			},
			startNumber: 11,
			startLane: 'O',
			armband: 'red',
			rank: 1,
			status: 0,
			time: '4:10.990',
			timeBehind: null,
			reskate: 0,
			medal: null,
			isOfficial: true,
			created: '2017-10-29T08:35:02.977036Z',
			modified: '2018-01-18T14:35:48.643409Z',
			laps: [
				{
					number: 1,
					time: '20.80',
					passageTime: '20.810'
				},
				{
					number: 2,
					time: '32.00',
					passageTime: '52.900'
				},
				{
					number: 3,
					time: '33.00',
					passageTime: '1:25.900'
				},
				{
					number: 4,
					time: '33.00',
					passageTime: '1:58.910'
				},
				{
					number: 5,
					time: '33.10',
					passageTime: '2:32.030'
				},
				{
					number: 6,
					time: '33.00',
					passageTime: '3:05.090'
				},
				{
					number: 7,
					time: '33.20',
					passageTime: '3:38.370'
				},
				{
					number: 8,
					time: '32.60',
					passageTime: '4:10.990'
				}
			]
		}
	];

	let races = [];

	for (let i = 0; i < response.length; i++) {
		if (response[i]['startNumber'] > response.length) {
			races.push([response[i]]);
		} else {
			const startNumber = response[i]['startNumber'];
			if (!races[startNumber]) {
				races[startNumber] = [];
			}
			races[startNumber].push(response[i]);
		}
	}
</script>

<div class="flex flex-col items-center">
	{#each races as race}
		<Race {race} />
	{/each}
</div>
