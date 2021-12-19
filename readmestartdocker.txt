 1146  top
 1147  docker 
 1148  docker   service
 1149  docker   service ls
 1150  docker   service scale dohweb=120
 1151  top
 1152  docker ps
 1153  docker   service scale dohweb=60
 1154  docker ps
 1155  clear
 1156  docker service ls
 1157  docker run -d -p81:80 -v /var/www/html:/var/www/html itsared/kongdebian:09
 1158  docker run -d -p82:80 -v /var/www/html:/var/www/html itsared/kongdebian:09
 1159  top
 1160  ls
 1161  docker ps
 1162  docker ps |more
 1163  docker stop 55
 1164  docker stop 0d
 1165  docker ps |more
 1166  docker stop 555
 1167  docker rm 555
 1168  docker rm 0d
 1169  docker ps
 1170  top
 1171  docker ps
 1172  top
 1173  docker service ls
 1174  docker ps
 1175  top
 1176  docker service ls
 1177  docker service
 1178  docker service scale dohweb=10
 1179  docker ps
 1180  clear
 1181  docker ps
 1182  clear
 1183  docker ps
 1184  top
 1185  docker ps
 1186  top
 1187  docker service rm dohweb
 1188  docker run -d -p 80:80 -v /var/www/html:/var/www/html itsared/kongdebian:09
 1189  docker ps
 1190  cd /var
 1191  cd www
 1192  cd html
 1193  ls
 1194  cd doh
 1195  ls
 1196  pwd
 1197  top
 1198  reboot
 1199  top
 1200  docker ps -a
 1201  docker ps -a |more
 1202  docker start de
 1203  docker ps -a |more
 1204  docker run -d -p 80:80 -v /var/www/html:/var/www/html itsared/kongdebian:09
 1205  docker ps
 1206  docker logs -f
 1207  docker 06 logs -f
 1208  docker  logs -f 06
 1209  reboot
 1210  top
 1211  clear
 1212  service php7.3-fpm status
 1213  service php7.3-fpm 
 1214  service 
 1215  check service php-fpm in container
 1216  top
 1217  docker service ps
 1218  docker service 
 1219  docker service docker stats $(docker ps|grep -v "NAMES"|awk '{ print $NF }'|tr "\n" " ") --no-stream
 1220  docker stats $(docker ps|grep -v "NAMES"|awk '{ print $NF }'|tr "\n" " ") --no-stream
 1221  docker ps
 1222  docker ps -a
 1223  docker ps -a |more
 1224  docker run -d -p 80:80 -v /var/www/html:/var/www/html itsared/kongdebian:09
 1225  docker ps
 1226  top
 1227  docker ps
 1228  doceker log -f 34
 1229  docker  log -f 34
 1230  docker ps
 1231  docker  logs -f 349
 1232  docker  logs -f 34
 1233  docker ps
 1234  docker stop 34
 1235  docker service create --name dohweb --replicas 10 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:09
 1236  docker ps
 1237  top
 1238  docker service ps redis
 1239  docker service ps php*
 1240  docker service ps nginx
 1241  docker service ps redis
 1242  docker ps
 1243  docker run -t -i e70 /bin/bash
 1244  top
 1245  docker ps
 1246  top
 1247  docker ps
 1248  top
 1249  cd /var
 1250  cd www
 1251  ls
 1252  cd html
 1253  ls
 1254  mkdir logs
 1255  ls
 1256  chmod 777 logs
 1257  ls
 1258  cd logs
 1259  ls
 1260  cat access.log 
 1261  clear
 1262  cat access.log 
 1263  clear
 1264  cat access.log 
 1265  ls
 1266  ls -l
 1267  cat error.log 
 1268  docker ps
 1269  docker service rm dohweb
 1270  docker ps
 1271  docker service create --name dohweb --replicas 10 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:09
 1272  ls
 1273  ls -l
 1274  rm *
 1275  ls
 1276  docker image ls
 1277  docker tag itsared/kongdebian:09   itared/complete:01
 1278  docker push   itared/complete:01
 1279  docker tag itsared/kongdebian:09   itared/kongdebian:50
 1280  docker push itared/kongdebian:50
 1281  docker ps
 1282  docker run -d -p81:80 -v /var/www/html:/var/www/html itsared/kongdebian:10
 1283  docker image
 1284  docker image ls
 1285  docker rm itsared/kongdebian:10
 1286  docker image rm itsared/kongdebian:10
 1287  docker ps
 1288  docker ps -a
 1289  docker stop d2
 1290  docker rm d2
 1291  docker image rm itsared/kongdebian:10
 1292  docker run -d -p81:80 -v /var/www/html:/var/www/html itsared/kongdebian:10
 1293  ls
 1294  cat access.log 
 1295  rm *
 1296  ls
 1297  ls 
 1298  ls
 1299  pwd
 1300  ls
 1301  docker ps
 1302  docker stop 12
 1303  docker start 12
 1304  ls
 1305  ls -l
 1306  cat access.log 
 1307  clear
 1308  cat access.log 
 1309  docker ps 
 1310  docker stop 12
 1311  docker rm 12
 1312  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:10
 1313  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 81:80 itsared/kongdebian:10
 1314  docker service create --name dohwebs --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 81:80 itsared/kongdebian:10
 1315  ls
 1316  ls -l
 1317  ls
 1318  ls -l
 1319  ls
 1320  chmod 777 *
 1321  ls
 1322  docker service 
 1323  docker service  ls
 1324  docker service rm dohwebs
 1325  docker service rm dohweb
 1326  docker service  ls
 1327  docker ps
 1328  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:10
 1329  top
 1330  ls
 1331  ls -l
 1332  cat error.log
 1333  ls -l
 1334  top
 1335  cd ..
 1336  ls
 1337  docker
 1338  ls
 1339  docker service ls
 1340  docker service rm dohweb
 1341  ls
 1342  chmod 777 -R doh
 1343  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:10
 1344  ls
 1345  cd logs
 1346  ls -l
 1347  docker 
 1348  docker ps
 1349  docker ps -a
 1350  docker image
 1351  docker image ls
 1352  docker 
 1353  docker inspect
 1354  docker rm
 1355  docker 
 1356  docker system prune
 1357  docker ps
 1358  docker rs
 1359  docker ps -a
 1360  docker service rm dohweb
 1361  docker ps -a
 1362  docker service create --name dohweb --replicas 10 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:10
 1363  docker ps
 1364  top
 1365  ls
 1366  pwd
 1367  cd /var
 1368  ls
 1369  cd html
 1370  cd www
 1371  ls
 1372  pwd
 1373  ls
 1374  cd html
 1375  ls
 1376  cd logs
 1377  ls
 1378  ls -l
 1379  docker ps
 1380  top
 1381  docker 
 1382  docker ps
 1383  ls
 1384  cd /var
 1385  ls
 1386  cd www
 1387  ls
 1388  cd html
 1389  ls
 1390  cd logs
 1391  ls
 1392  ls -l
 1393  top
 1394  docker ps
 1395  pwd
 1396  ls
 1397  cd /var
 1398  ls
 1399  cd www
 1400  ls
 1401  cd html
 1402  ls
 1403  cd logs
 1404  ls
 1405  cat access.log 
 1406  cd /var/www/html
 1407  ls
 1408  cd logs
 1409  ls
 1410  cat access.log |more
 1411  cat access.log 
 1412  top
 1413  ls
 1414  pwd
 1415  docker ps
 1416  docer exe -it be bin/sh
 1417  docer exe -it be /bin/sh
 1418  docer exe -it be4 /bin/sh
 1419  docer exec -it be4 /bin/sh
 1420  docker exec -it be4 /bin/sh
 1421  ls
 1422  date
 1423  cd /
 1424  ls
 1425  find ./ -name localtime
 1426  cd /etc
 1427  ls
 1428  docker exec -it be4 /bin/sh
 1429  nano timezone
 1430  ls -l ti*
 1431  cate timezone
 1432  cat timezone
 1433  top
 1434  ls
 1435  pwd
 1436  cd /var
 1437  ls
 1438  cd www
 1439  ls
 1440  cd html
 1441  ls
 1442  cd logs
 1443  ls
 1444  cat error.log
 1445  cat access.log 
 1446  clear
 1447  ls
 1448  df -h
 1449  ls
 1450  cd ..
 1451  ls
 1452  du doh
 1453  du -s doh
 1454  du -s -m doh
 1455  du -s -f doh
 1456  man du 
 1457  du -s -m doh
 1458  du -s -k doh
 1459  du -s -m doh
 1460  top
 1461  cd /etc
 1462  ls
 1463  ls d*.*
 1464  ls t*.*
 1465  ls l*.*
 1466  ls -l /etc/localtime
 1467  cd /usr/share/zoneinfo/
 1468  ls
 1469  ls -l
 1470  nano /etc/localtime
 1471  nano localtime 
 1472  cat /etc/timezone
 1473  nano /etc/timezone 
 1474  cd /etc
 1475  ls
 1476  ls -l timezone
 1477  nano timezone 
 1478  docker ps
 1479  docker service ls
 1480  docker service rm dohweb
 1481  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:11
 1482  ls
 1483  docker ps
 1484  docker exec -it 98
 1485  docker exec -it 98 /bin/sh
 1486  ls
 1487  cd /var
 1488  cd www/
 1489  cd html/
 1490  ls
 1491  cd logs/
 1492  ls
 1493  cat access.log 
 1494  docker service rm dohweb
 1495  docker service ls
 1496  docker service create --name dohweb --replicas 3 --mount type=bind,src=/var/www/html,dst=/var/www/html   -p 80:80 itsared/kongdebian:12
 1497  top
 1498  dokcer ps
 1499  docker  ps
 1500  cat access.log 
 1501  top
 1502  docker ps
 1503  clear
 1504  docker ps
 1505  clear
 1506  docker ps
 1507  cat access.log 
 1508  ls -l
 1509  top
 1510  ls
 1511  pwd
 1512  cd /var
 1513  ls
 1514  cd www
 1515  ls
 1516  cd html
 1517  ls
 1518  du -s -m doh
 1519  top
 1520  docker service ls
 1521  docker ps
 1522  clear
 1523  docker ps
 1524  top
 1525  docker ps
 1526  cele
 1527  clear
 1528  docker ps
 1529  df -u
 1530  df
 1531  df -h
 1532  top
 1533  docker ps
 1534  top
 1535  docker ps
 1536  ls
 1537  pwd
 1538  ls
 1539  cd /var
 1540  ls
 1541  cd www
 1542  ls
 1543  cd html
 1544  ls
 1545  cd doh
 1546  ls
 1547  cd ..
 1548  ls
 1549  du -sh doh
 1550  du -s doh
 1551  du -h doh
 1552  ls
 1553  DiffMerge
 1554  diff
 1555  top
 1556  diff
 1557  colordiff
 1558  ls
 1559  cd /
 1560  find /var/www/html/doh_Backup/ -type f -exec md5sum {} + | sort -k 2 > dir1.txt
 1561  ls
 1562  cd /
 1563  find ./-name dir1.txt
 1564  find ./ -name dir1.txt
 1565  cat dir1.txt 
 1566  top
 1567  docker ps
 1568  history
 1569  history |moe
 1570  history |more
 1571  exit
 1572  cd /var
 1573  lw
 1574  cd www
 1575  ls
 1576  cd html
 1577  ls
 1578  cd doh
 1579  ls
 1580  cd public
 1581  ls
 1582  docker ps
 1583  ls
 1584  pwd
 1585  cd /var
 1586  ls
 1587  cd www
 1588  ls
 1589  cd html
 1590  ls
 1591  cd doh
 1592  ls
 1593  cd ..
 1594  ls
 1595  mkdir conf
 1596  chmod 777 -R conf
 1597  ls
 1598  cd ..
 1599  ls
 1600  mkdir temp
 1601  cd temp
 1602  git clone https://github.com/dohnetwork/kongdebian12.git
 1603  ls
 1604  cd kongdebian12/
 1605  ls
 1606  cp default.conf /var/www/html/conf/
 1607  cd ..
 1608  ls
 1609  cd html/
 1610  ls
 1611  cd conf
 1612  ls
 1613  ls -l
 1614  chmod 777 *
 1615  ls
 1616  ls -l
 1617  docker ps
 1618  docker stop d9 
 1619  docker ps
 1620  docker run --name mynginx1 -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-123 -d -v /var/www/html:/var/www/html -p 85:80  itsared/kongdebian:13
 1621  docker ps
 1622  docker ps -a
 1623  docker ps
 1624  docker  exec -it 401 /bin/sh
 1625  ls
 1626  docker ps
 1627  docker logs 401
 1628  docker run   -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:13
 1629  docker ps
 1630  docker ps -a
 1631  docker ps
 1632  docker ps -a
 1633  docker stop bc
 1634  docker rm bc
 1635  docker rm 1f
 1636  docker rm lf
 1637  docker rm 78
 1638  docker rm 2f
 1639  docker rm fb6
 1640  docker stop bc
 1641  docker ps -a
 1642  docker rm lfb
 1643  docker rm 1fb812b3d35d 
 1644  docker rm 34d6577adbce  
 1645  docker ps -a
 1646  docker rm 349
 1647  docker ps
 1648  ls
 1649  docker ps
 1650  clear
 1651  docker ps
 1652  docker run --name mynginx2 -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-124 -d -v /var/www/html:/var/www/html -p 99:80  itsared/kongdebian:14
 1653  docker ps
 1654  docker exec -it bb /bin/sh
 1655  docker ps
 1656  docker exec -it 40 /bin/sh
 1657  ls
 1658  clear
 1659  ls
 1660  docker ps
 1661  docker run --name  -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:12
 1662  docker run   -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:12
 1663  docker ps
 1664  clear
 1665  docker ps
 1666  docker stop 65 
 1667  docker rm 65 
 1668  docker stop bb
 1669  docker rm bb
 1670  docker stop 401
 1671  docker rm 401
 1672  docker ps
 1673  docker run --name  -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:14
 1674  docker run   -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:14
 1675  docker ps
 1676  docker logs 7b
 1677  docker ps
 1678  docker logs 7b
 1679  docker ps
 1680  docker logs 7b
 1681  docker ps
 1682  docker stop 7b
 1683  docker rm 7b
 1684  docker image ls
 1685  docker image rm itsared/kongdebian:14
 1686  docker image rm itsared/kongdebian:13
 1687  dokcer ps
 1688  docker ps
 1689  docker ps -a
 1690  docker ps
 1691  docker run --name  -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:15
 1692  docker ps
 1693  docker ps -a
 1694  docker run   -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:15
 1695  docker ps
 1696  docker ps -a
 1697  docker run   -d -v /var/www/html:/var/www/html -p 84:80  itsared/kongdebian:15
 1698  docker ps
 1699  docker ps -a
 1700  docker rm b2
 1701  docker rm 731
 1702  docker rm 0c
 1703  docker ps -a
 1704  docker start d9
 1705  docker ps
 1706  pwd
 1707  cd /var
 1708  ls
 1709  cd www
 1710  ls
 1711  cd html
 1712  ls
 1713  cd conf
 1714  ls
 1715  nano default.conf 
 1716  ls
 1717  docker ps
 1718  docker run  -d -v /var/www/html:/var/www/html -p 88:80  itsared/kongdebian:16
 1719  docker ps
 1720  docker ps -a
 1721  docker logs 09
 1722  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-129 -d -v /var/www/html:/var/www/html -p 85:80  itsared/kongdebian:16
 1723  docker ps
 1724  docker logs 32
 1725  docker ps
 1726  docker exec -it 32 /bin/sh
 1727  docker ps
 1728  clear
 1729  docker ps
 1730  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-128 -d -v /var/www/html:/var/www/html -p 89:80  itsared/kongdebian:17
 1731  docker ps
 1732  docker logs 59
 1733  docker ps
 1734  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-12 -d -v /var/www/html:/var/www/html -p 86:80  itsared/kongdebian:18
 1735  docker ps
 1736  docker logs 49
 1737  docker ps
 1738  docker exec -it 49 /bin/sh
 1739  docker ps
 1740  docker exec 49 /bin/sh
 1741  ls
 1742  pwd
 1743  cd /
 1744  ls
 1745  cd etc
 1746  ls
 1747  ip a
 1748  clear
 1749  ls
 1750  cd /
 1751  find ./ -name agent.conf
 1752  nano
 1753  nano /var/lib/docker/overlay2/237b311df31de3a6b8aa71a0159356818046fe90a2503fcbd58b747441328712/merged/etc/amplify-agent/agent.conf
 1754  docker ps
 1755  ls
 1756  docker ps
 1757  docker exec -it 49 /bin/sh
 1758  SCRIPT_NAME=/status SCRIPT_FILENAME=/status QUERY_STRING= REQUEST_METHOD=GET cgi-fcgi -bind -connect 127.0.0.1:9090
 1759  clear
 1760  docker ps
 1761  docker exec -it d9
 1762  docker exec -it d9 /bin/sh
 1763  docker ps
 1764  docker exec -it d9 /bin/sh
 1765  docker ps
 1766  docker stop d9
 1767  docker start d9
 1768  docker exec -it d9 /bin/sh
 1769  docker ps
 1770  docker stop d9
 1771  docker start d9
 1772  docker exec -it d9 /bin/sh
 1773  docker ps
 1774  clear
 1775  docker
 1776  docker ps
 1777  docker exec -it d9 /bin/sh
 1778  docker ps
 1779  docker stop d9
 1780  ls
 1781  docker ps
 1782  docker start d9
 1783  docker exec -it d9 /bin/sh
 1784  docker ps
 1785  docker stop d9
 1786  docker start d9
 1787  docker exec -it d9 /bin/sh
 1788  docker stop 49a
 1789  docker rm 49a
 1790  docker stop 590
 1791  docker rm 59
 1792  docker stop 320
 1793  docker rm 320
 1794  docker ps
 1795  docker stop 8d8
 1796  docker ps
 1797  docker start 8d8
 1798  docker ps
 1799  clear
 1800  docker ps
 1801  docker logs d9
 1802  docker exec -it d9 /bin/sh
 1803  docker ps
 1804  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-12 -d -v /var/www/html:/var/www/html -p 86:80  itsared/kongdebian:17
 1805  docker ps
 1806  docker exec ps
 1807  docker exec ps 5b
 1808  docker exec ps 5b8
 1809  docker exec ps 5b8 /bin/sh
 1810  docker exec -it 5b8 /bin/sh
 1811  docker ps
 1812  docker stop 5b
 1813  docker rm 5b
 1814  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service-12 -d -v /var/www/html:/var/www/html -p 86:80  itsared/kongdebian:16
 1815  docker ps
 1816  docker logs cd5
 1817  docker exec -it cd5 /bin/sh
 1818  docker ps
 1819  docker stop cd5
 1820  docker start cd5
 1821  docker exec -it cd5 /bin/sh
 1822  docker ps
 1823  docker stop cd5
 1824  docker startcd5
 1825  docker start cd5
 1826  docker exec -it cd5 /bin/sh
 1827  docker ps
 1828  docker stop cd5
 1829  docker start cd5
 1830  docker ps
 1831  docker exec -it cd5 /bin/sh
 1832  docker ps
 1833  docker stop cd
 1834  docker start cd
 1835  docker exec -it cd5 /bin/sh
 1836  docker ps
 1837  docker stop cd5
 1838  docker start cd5
 1839  docker exec cd ls
 1840  docker exec cd service --status-all
 1841  docker exec cd /bin/sh
 1842  ls
 1843  nano etc
 1844  cd /etc
 1845  ls
 1846  cd nginx
 1847  ls
 1848  cd nginx
 1849  ls
 1850  pwd
 1851  cd nginx
 1852  docker ps
 1853  docker exec -it cd /bin/sh
 1854  docker ps
 1855  docker stop cd
 1856  docker start cd
 1857  docker exec cd --status-all
 1858  docker exec cd ls
 1859  docker exec cd service --status-all
 1860  docker exec -it cd /bin/sh
 1861  docker stop cd
 1862  docker start cd
 1863  docker ps
 1864  exit
 1865  df -h
 1866  docker image ls
 1867  docker image rm 39b
 1868  docker image rm 0d5
 1869  docker image rm 6ce
 1870  docker image rm 326
 1871  docker image rm 1b
 1872  df -h
 1873  pwd
 1874  ls
 1875  cd /
 1876  ls
 1877  mkdir Docker
 1878  ls
 1879  cd Docker
 1880  ls
 1881  cd ..
 1882  ls
 1883  chmod 777 Docker/
 1884  ls
 1885  chmod 777 -R Docker/
 1886  cd Docker/
 1887  ls
 1888  docker ps
 1889  docker stop cd
 1890  docker rm cd
 1891  docker image ls
 1892  docker image rm 6ce
 1893  docker rm cd5
 1894  docker ps -a
 1895  docker rm 4c5
 1896  docker rm 099
 1897  docker ps
 1898  ls
 1899  docker image ls
 1900  docker image rm 6c
 1901  df -h
 1902  ls
 1903  docker ps
 1904  pwd
 1905  df -h
 1906  cd /Docker/
 1907  git clone https://github.com/dohnetwork/kongdebian12.git
 1908  ls
 1909  docker ps
 1910  ls
 1911  cd kongdebian12/
 1912  ls
 1913  cd ..
 1914  chmod 777 -R kongdebian12/
 1915  cd kongdebian12/
 1916  ls
 1917  nano Dockerfile
 1918  ls
 1919  pwd
 1920  ls
 1921  nano Dockerfile
 1922  ls
 1923  nano entrypoint.sh
 1924  nano Dockerfile
 1925  ls
 1926  nano entrypoint.sh 
 1927  ls
 1928  docker image ls
 1929  docker build -t kongagent 
 1930  ls 
 1931  cd ..
 1932* chmod 777 -R kongdebian .
 1933  cd kongdebian12/
 1934  ls
 1935  docker build -t kongagent .
 1936  ls
 1937  nano Dockerfile
 1938  docker build -t kongagent .
 1939  ls
 1940  nano Dockerfile
 1941  docker build -t kongagent .
 1942  nano Dockerfile
 1943* docker build -t kongagent .docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1944  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1945  docker ps
 1946  docker ps -a
 1947  ls
 1948  nano Dockerfile
 1949  docker build -t kongagent .
 1950  docker ps -a
 1951  docker rm 283
 1952  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1953  docker ps
 1954  docker exec a5c service --status-all
 1955  docker exec -it a5c /bin/sh
 1956  docker ps
 1957  nano Dockerfile
 1958  docker build -t kongagent .
 1959  docker ps
 1960  docker stop a5
 1961  docker rm a5
 1962  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1963  docker ps
 1964  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 83:80  kongagent 
 1965  docker ps
 1966  docker stop 97
 1967  docker rm 97
 1968  docker stop d7
 1969  docker rm  d7
 1970  docker ps
 1971  nano Dockerfile
 1972  docker build -t kongagent .
 1973  nano Dockerfile
 1974  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 83:80  kongagent 
 1975  docker ps
 1976  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1977  docker ps
 1978  nano Dockerfile
 1979  docker ps
 1980  nano Dockerfile
 1981  docker ps
 1982  nano Dockerfile
 1983  docker ps
 1984  nano Dockerfile
 1985  docker build -t kongagent .
 1986  docker ps
 1987  docker stop c33
 1988  docker rm c33
 1989  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 1990  docker stop 0e
 1991  docker rm 0e
 1992  docker ps
 1993  nano Dockerfile
 1994  docker ps
 1995  nano Dockerfile
 1996  docker ps
 1997  docker stop 9d
 1998  docker rm 9d
 1999  docker build -t kongagent .
 2000  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2001  docker ps
 2002  docker stop 4c
 2003  docker stop f6
 2004  docker rm f6
 2005  nano Dockerfile
 2006  docker build -t kongagent .
 2007  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2008  docker ps
 2009  docker stop f4
 2010  docker rm f4
 2011  nano Dockerfile
 2012  docker build -t kongagent .
 2013  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2014  docker ps
 2015  nano Dockerfile
 2016  docker ps
 2017  docker stop 1b
 2018  docker rm 1b
 2019  nano Dockerfile
 2020  docker build -t kongagent .
 2021  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2022  docker ps
 2023  docker stop 547
 2024  docker rm 547
 2025  nano Dockerfile
 2026  docker ps
 2027  docker build -t kongagent .
 2028  ls
 2029  nano start.sh 
 2030  ls
 2031  docker ps
 2032  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2033  docker logs 31
 2034  docker exec 31 service --status-all
 2035  ls
 2036  pwd
 2037  ls
 2038  nano start.sh 
 2039  docker
 2040  docker ps
 2041  docker stop 31
 2042  docker rm 31
 2043  docker build -t kongagent .
 2044  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2045  docker ps
 2046  docker exec 724 service --status-all
 2047  docker ps
 2048  ls
 2049  nano start.sh 
 2050  docker ps
 2051  docker stop 72
 2052  docker rm 72
 2053  nano start.sh 
 2054  docker build -t kongagent .
 2055  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2056  docker ps
 2057  docker run   -d -v /var/www/html:/var/www/html -p 82:80  kongagent 
 2058  docker ps
 2059  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 83:80  kongagent 
 2060  docker ps
 2061  docker sp
 2062  docker ps
 2063  docker exec 4c service --status-all
 2064  docker exec 4c8 service --status-all
 2065  dokcer ps
 2066  docker ps
 2067  clear
 2068  docker ps
 2069  ls
 2070  docker ps
 2071  docker exec -it 4c /bin/sh
 2072  docker exec it 4c /bin/sh
 2073  docker exec -it 4c8 /bin/sh
 2074  docker ps
 2075  docker stop 4c8
 2076  docker start 4c8
 2077  docker ps
 2078  ls
 2079  docker ps
 2080  docker exec -it 4c8 /bin/sh
 2081  ls
 2082  nano nginx.conf
 2083  ls
 2084  chmod 777 nginx.conf 
 2085  ls
 2086  nano Dockerfile
 2087  docker exec -it 4c8 /bin/sh
 2088  docker ps
 2089  docker build -t kongagent .
 2090  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service -d -v /var/www/html:/var/www/html -p 84:80  kongagent 
 2091  docker ps
 2092  docker stop 4c8
 2093  docker ps
 2094  docker exec -it 32 /bin/sh
 2095  ls
 2096  docker ps
 2097  ls
 2098  docker ps
 2099  docker exec -it 32 /bin/sh
 2100  apt-get install libfcgi0ldbl
 2101  docker ps
 2102  docker exec -it 32 /bin/sh
 2103  top
 2104  docker exec -it 32 /bin/sh
 2105  ls
 2106  docker ps
 2107  docker stop 32d
 2108  docker start 32d
 2109  docker logs 32d
 2110  docker exec -it 32d /bin/sh
 2111  ls
 2112  nano Dockerfile
 2113  docker image ls
 2114  docker build -t kongagent .
 2115  docker
 2116  docker ps
 2117  ls
 2118  docker ps
 2119  docker run  -e API_KEY=f3875cd7ada2f3258c5ac8df964bfde5 -e AMPLIFY_IMAGENAME=my-service1 -d -v /var/www/html:/var/www/html -p 85:80  kongagent 
 2120  docker ps
 2121  docker exec -it 14 /bin/sh
 2122  docker ps
 2123  docker stop 14d
 2124  docker start 14d
 2125  docker ps
 2126  docker exec -it 14 /bin/sh
 2127  ls
 2128  docker ps
 2129  docker stop 32d
 2130  docker rm 32d
 2131  docker ps
 2132  docker stop d9a
 2133  docker ps
 2134  docker rm d9a
 2135  docker ps
 2136  docker service
 2137  docker service ls
 2138  ls
 2139  pwd
 2140  ls
 2141  history |more
 2142  pwd
 2143  cd ..
 2144  ls
 2145  history > readmestartdocker.txt
